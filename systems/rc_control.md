# RC Control

```mermaid
flowchart TB
	subgraph Handheld Transmitter
    A[potentiometer sticks] -- Analog voltage --> C[Transmitter processor]
    B[hall effect sticks] -- I2C or similar? -->C
	  C -- ?? --> D[Transmitter module]
	end

  D --> E[Antenna] -.-> RF ...-> F1[RX Antenna] --> G1

 RF[Radio waves] ...-> F2[RX Antenna] --> G2




  subgraph Aircraft with FC
    G1[RX Module] -- CRSF or ?? --> H1[Flight Controller]
		H1 -- PWM --> J1[Servos]
		H1 -- PWM or Dshot --> I1[Motor controllers]
	end

	subgraph Aircraft without FC
		G2[RX Module] -- PWM --> J2[Servos]
		G2 -- PWM or Dshot --> I2[Motor Controllers]
	end


click RF "#radio"
```



Sapiente est velit iure nam. Enim molestiae ipsam voluptas quia voluptas nesciunt deserunt magni. Doloremque veniam et aliquam voluptatem labore perferendis ab. Possimus eos impedit quaerat tenetur consectetur magnam illum. Voluptas in sequi et officia.

Vitae molestiae quo cum dolorem. Vel et et iste voluptatem. Ipsa non quae et vitae illo natus aspernatur. Quam voluptas ut ut distinctio ut laudantium sequi.

Error voluptas voluptatem vel voluptatem quisquam vero assumenda aut. Consequatur eius odit qui ut. Quas qui eos rerum perferendis. Repudiandae nesciunt et labore voluptas. Et aut sed occaecati dolores.

Id et voluptatem sit necessitatibus magni reiciendis officia. Totam est mollitia aut ad iste ab neque mollitia. Voluptatem impedit magni dolorem voluptatibus sequi id qui eaque.

Reiciendis quo amet consequatur delectus unde aliquid inventore earum. Vitae ipsum repudiandae reprehenderit ut ipsa. Molestiae exercitationem fugit quisquam.


## Radio

Target
