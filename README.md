# process mapping

```mermaid
graph TD
    A[Start] --> B(Data Preparation)
    B --> C(Encryption)
    C --> D(Adaptive Embedding)
    D --> E(Embedding Capacity Evaluation)
    E --> F(PSNR Measurement)
    F --> G(Experimental Evaluation)
    G --> H(Analysis and Interpretation)
    H --> I(Validation and Verification)
    I --> J[End]

    B --> |1| B1(Select color images)
    B --> |2| B2(Prepare text data)

    C --> |1| C1(Encrypt images using RSA)
    C --> |2| C2(Maintain confidentiality and integrity)

    D --> |1| D1(Implement adaptive embedding)
    D --> |2| D2(Optimize embedding capacity)

    E --> |1| E1(Calculate embedding capacity)
    E --> |2| E2(Determine max text data per pixel)

    F --> |1| F1(Reconstruct encrypted images)
    F --> |2| F2(Measure PSNR)

    G --> |1| G1(Conduct experiments)
    G --> |2| G2(Record experimental data)

    H --> |1| H1(Analyze experimental results)
    H --> |2| H2(Interpret findings)

    I --> |1| I1(Validate experimental results)
    I --> |2| I2(Verify methodologies)
```
