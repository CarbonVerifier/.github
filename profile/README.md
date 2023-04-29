# Carbon Verifier

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

Introducing CarbonVerifier, a project that utilizes IoT devices and blockchain technology to generate carbon credits and incentivize climate action.

Our project aims to provide a transparent and secure way for companies to offset their carbon emissions, eliminating the need for trust in third-party verification. By monitoring climate action projects with IoT sensors, we can accurately measure emissions and mint carbon tokens based on the sensor readings.

The carbon tokens serve as proof of carbon offsetting and can be traded on the blockchain. Anyone can verify a company's emissions and validate the carbon token, promoting greater transparency and auditability. Furthermore, the democratization of the carbon offset market, which allows anyone to purchase these credits, not just companies, encourages more widespread sustainable practices.

CarbonVerifier combines the power of IoT and blockchain technology to create a more efficient and effective way to tackle climate change. Our project promotes sustainable practices and encourages companies to take action to reduce their carbon footprint.

Join us in the fight against climate change, as we use technology to create a more sustainable future. Let's make carbon offsetting accessible to all and create positive change for the planet.

## Verifying carbon offsets
CarbonVerifier's business logic relies on a smart contract that receives and analyzes sensor data to determine whether a company is eligible for carbon credit token minting. The smart contract is unique to each company and checks the sensor readings against predetermined threshold values during a specified period.

For natural reserves, CarbonVerifier uses various sensors, such as a sound sensor that has a threshold of 80 decibels to detect chainsaw and other damaging human activities. In addition, a temperature sensor detects 21 to 30 degrees Celsius, air humidity ranges from 80-80% for optimal development in a rainforest, and soil humidity should be within the range of 30-35% for good plant growth in tropical forests. CarbonVerifier also sets a threshold of 350-440 ppm of CO2 in the air to ensure that the rainforest is absorbing carbon at a sufficient rate.

In the case of wind turbines, CarbonVerifier takes into account electricity grid sensors that estimate CO2 emissions based on the electricity generated, as well as CO2 levels in the air. This approach ensures that the turbines are reducing CO2 emissions effectively.

If the average sensor readings exceed the predetermined thresholds, the smart contract will not mint any carbon credit tokens. However, if the average sensor readings remain within the acceptable thresholds, the smart contract will mint new carbon credit tokens for the corresponding company address.

CarbonVerifier's approach provides transparency and trust in carbon emission offsetting. Furthermore, the ability for anyone to buy carbon credit tokens, not just other companies, incentivizes and stimulates the market for climate change efforts, promoting more sustainable practices and a more sustainable future.
