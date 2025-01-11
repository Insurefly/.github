<!-- ![brand]() -->
<p align="center">
  <img src="https://github.com/Insurefly/Frontendd/blob/275659ee50ef1814d1f388e94b1867f11da70955/public/brand.png" alt="Alt Text" />
</p>

<h4 style="text-align:center;" align="center">Wingsurance is a platform that simplifies and decentralizes flight insurance. By leveraging blockchain technology and Chainlink oracles, Wingsurance ensures transparency, reliability, and fairness in every step of the process.</h4>



## What it Does

Wingsurance enables users to purchase insurance for their flights and claim transparent insurance coverage seamlessly in case of delays or cancellations. The platform calculates insurance premiums and verifies claims using real-time flight data fetched via Chainlink oracles. This ensures fairness and precision for every policy issued. By fetching real-time data from trusted external sources using Chainlink functions, the platform accurately determines premiums and validates claims based on predefined rules and triggers.


## How we built it

Wingsurance is comprised of three smart contracts, each serving a specific purpose within the platform:

- [ ] **FlightInsurance**: The FlightInsurance contract facilitates the creation and claiming of flight insurance policies. It allows users to:
- Create insurance policies by providing flight details and premium payments.
- File insurance claims in the case of flight cancellations or delays.
- Use Chainlink oracles to fetch flight data for accurate claims processing.

- [ ] **InsuranceManager**: The InsuranceManager contract handles the core insurance operations:
- Calculates insurance premiums using predefined algorithms and user-provided base premiums.
- Verifies eligibility for insurance claims with help of real time data using Chainlink Functions.
- Issues insurance claims based on valid data and ensures transparent policy management.

- [ ] **FundManager**: The FundManager contract serves as the centralized treasury to manage platform funds:
- Holds funds received from the InsuranceManager and StakingManager contracts.
- Allocates funds for insurance claims, staking rewards, and other financial operations.
- Ensures liquidity and secure fund distribution throughout the system.


These smart contracts collaborate seamlessly to build a robust and holistic platform for creating flight insurance, managing policy and claim operations, and fostering transparency through decentralization. Together, they ensure reliability, fairness, and trust in every interaction, redefining how flight insurance is accessed and managed.


Through these smart contracts, Wingsurance offers travelers an easy-to-use platform for creating flight insurances with transparent and fully automated claims processing, ensuring a seamless and reliable experience in the decentralized flight insurances.


## Challenges we ran into

Developing Wingsurance was not without its challenges. Here are the main struggles we encountered and successfully resolved:

- [ ] **Adding Staking Funtionality**: The platform offers a staking mechanism where investors can stake their tokens and earn WING tokens as staking rewards. By participating in the staking program, investors contribute liquidity to the platform and help secure the network. Staking rewards are distributed periodically, incentivizing long-term participation and fostering a vibrant community. However, due to time constraints during development, we were unable to fully integrate the staking functionality. Nonetheless, this obstacle provided us with valuable insights and has informed our plans for future improvements.

- [ ] **Integration Complexity**: Integrating multiple components and functionalities within Agrosurance proved to be time-consuming due to the complexity involved. Despite the challenges, we persevered and successfully integrated the necessary features.

## Accomplishments that we're proud of

We take great pride in the accomplishments we have achieved with Agrosurance. Here are the key aspects we are proud of:

- [ ] **Seamless Integration with Chainlink Functions**: Despite being our first time working with Chainlink functions, we quickly embraced the learning curve and successfully integrated their functions into our platform. This demonstrates our ability to adapt and learn new technologies efficiently.

- [ ] **Transparency and On-Chain Storage**: By storing the insurance premium calculation and claim verification codes on the blockchain, we have established a transparent and immutable system. This ensures that all participants can access and audit the code, fostering trust and transparency within the platform.

- [ ] **User-Friendly Interface**: We have invested significant effort into creating an intuitive and user-friendly interface for Wingsurance. Our goal was to make it easy for travellers, investors, and other users to navigate the platform, stake their Matic tokens, and manage their insurance policies effortlessly.


## What we learned 

Throughout the development of Wingsurance, our team has gained valuable knowledge and insights. Here are some of the key learnings we acquired during the project:

- [ ] **Chainlink Integration**: We had the opportunity to explore and integrate Chainlink functions into our platform. This experience taught us about decentralized oracles and how they enable secure and reliable data retrieval and off-chain computations. We learned how to leverage Chainlink to fetch real-world data and integrate it into our smart contracts.

- [ ] **Insurance and Funds Management**: Developing the InsuranceManager and FundsManager contracts helped us understand the complexities of managing both insurance policies and liquidity in a decentralized system. We learned the importance of proper premium allocation, transparent reward distribution, and the challenges of maintaining sufficient funds for smooth claims processing and platform stability.

- [ ] **Time Management and Prioritization**: Throughout the project, we faced time constraints and had to prioritize certain features over others. We learned how to effectively manage our time, make informed decisions, and ensure that the core functionalities were implemented within the given timeframe.
