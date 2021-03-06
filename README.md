# Software_Development_Lifecycles
## The Different Types of Software Life Cycles
### Waterfall Model
#### What is the Waterfall Lifecycle?
The waterfall software development lifecylce describes a sequential process that follows certain stages in a linear downward order (like a waterfall), with little flexibility, meaning that to progress to the next step you must complete the one prior and you cannot jump between stages. The logical nature of the sequential process, in the waterfall method, is why the waterfall method is commonly used as the design process in the programming industry. The stages are, in order:
* Requirement gathering and analysis: The required resources for the project are developed and are documented.
* System Design: The requirements from the previous stage are studied and the system is then designed, the design helps specify what hardware and system requirements and helps in defining the architecture of the system.
* Implementation: With inputs from the system design, the system is the designed in small parts called units. Each unit is developed and tested for functionality.
* Integration and testing: All the units developed in the last phase are then integrated into the same system, the entire system is then tested for any errors.
* Deployment of the system: Once the system has been fully developed, the product is then released to the consumer market
* Maintanence: The system may still encounter errors while being released, these errors can be corrected by released patched versions of the system.
#### Advantages of the Waterfall Lifecycle
While the waterfall method is losing popularity over the years, it can still provide a number of benefits, particularly for larger projects and businesses that require the stringent stages and deadlines included with this method.
* Forces Structured Organization: The waterfall model forces the project, even the team working on the project, to be very disciplined in its design and structure. Most large projects will need to include detailed procedures to manage all aspects of the project from the requirement gathering to the maintanence of the project.
* Allows Early Design Changes: As the beggining stages of the model are focused on planning for development, alterations to the project can be made during these stages, since no coding or implementation has actually taken place. However it is more difficult to to make changes in the later stages of the model.
* Suited for Milestone-Focused Development: As the waterfall model is set in a linear structure, it is suited for teams that work well under a milestone and date-focused work paradigm. The model allows teams to understand and prepare for each stage of the process, and to easily create a time line for the entire process and assign particular milestones in said timeline.
* Suited for Large Software Development Projects: 
#### Disadvantages of the Waterfall Model
* Nonadaptive Design Constraints: The biggest flaw of the waterfall lifecycle is its inherent lack of adaptability in all of its stages. For instance if in the testing stage of the model reveals a fundamental flaw in the software, it would require a dramatic leap backwards in the lifecycle which would then force the team to go back through the respective stages again, dramatically increasing the work time of the development of the software and interfering with any planned deadlines.
* Ignores Mid-process User/Client Feedback: Due to the strict nature of the step-by-step process enforced by the cycle, a issue that is hard to solve is that the user feedback is only given late into the lifecycle, and can even be given too late. If an unforseen requirement or a change from the client is discovered the project will be forced to revert to previous stages to apply the changes which would be costly and time consuming for the organization.
* Delayed Testing Period: The waterfall model only allows testing to occur until quite late in the development process. This means that most bugs/ design issues wont be discovered until very late in the lifecycle.

### Evolutionary/Iterative Lifecycle
#### What is the Evolutionary/Iterative Lifecycle?
The iterative lifecycle is a method of developing software, this method starts with a simple construction of a small set of the softwares requirements and iteratively enhances the basic software by creating evolutions of the original version until the software is fully complete and meets all the requirements. The iterative life cycle model does not start with all the specifications of the software being planned out, instead development begin by only specifying and developing a section of the software, which is then observed and tested, to see what requirements would be required to improve upon the software. This process is repeated  producing a new version at the end of every iteration, with design modifications and new functions.
#### Advantages of the Iterative Lifecycle
* Obtain Results Very Early in Development: This is because in the very early stages of development in the iterative life cycle, there is a working model, this makes finding functional or design flaws simpler. Finding these issues in early development allows the developer to fix these issues before they affect the larger versions of the software.
* Suited for Larger Projects: This is because the larger project can be broken down into seperate sections of software that can then be iteratively developed.
* Allows Customer Feedback during Devlopment: As the iterative life cycle creates multiple versions of the same software, versions can be sent to clients to obtain feedback from them, allowing the developer to see if they are developing their software in the right direction.
#### Disadvantages of the Iterative Lifecycle
* Not Suitable for Small Projects: This is because smaller projects are harder to breakdown into smaller sections to develop.
* End of Project may not be known: This is a risk because there is not a set plan of how the project will function once it has been fully developed, which adds the risk of the final version of the project not being acceptable to the client which would be a waste of all the resources put into development.

### The Spiral Lifecycle
#### What is the Spiral Lifecycle
The spiral model uses elements from the iterative structure from the evolutionary model and the controlled systematic progress of waterfall method. The process involves going through the incremental processes, then once all parts have been completed the,iterations of the processes occur (like a spiral) until the software is deemed complete.
The stages of the spiral life cycle are as follows:
* Identification: This phase starts by gathering the required resources and business requirements for the project. In later iterations this phase as the software is developed, identification of additional requirements for the new version of the software are found. This phase also includes understanding the system requirements by using communication with the desired market for the software, at the end of the spiral lifecycle the product is released in the indentified market.
* Design: This phase begins with the concept design for first iteration of the spiral lifecycle. This design process involves the architectural design, logical design of modules and the phsyical product design and the design of the iteration in the spiral.
* Construct or Build: This phase involves the production of the actual software product at every iteration. In the first iteration when there has been no development on the software, a POC (Proof of Concept) is developed so customer feedback can be recieved.
* Evaluation and Risk Analysis: The Risk analysis in this phase includes identifying, estimating and monitoring  technical feasibility and management risks. After testing the build, at the end of first iteration, the customer/client evaluates the software and provides feedback.
#### Advantages of the Spiral Lifecycle
* It is Flexible: The spiral lifecycle allows new elements of the product to be added during the development process, when they become known, assuring that there is no conflict with previous requirements in the design.
* Allows the use of Prototypes: During the lifecycle multiple builds of the product will be created with each iteration of the spiral, allowing users to test earlier prototypes of the product ensuring the reliability of the final product.
#### Disadvantages of the Spiral Lifecycle
* Not Suitable for Smaller Projects: The spiral lifecycle has quite a high cost due to the length of the model, meaning that this type of lifecycle is not suited for smaller projects as the final product may not justify the cost.
* Requires Excessive Documentation: As the spiral model could go on indefintely and iterates stages, documentation created while using this model, will be extensive as it will include every iteration of each step of the model, which will require time to be set out of the development process to complete.
#### How Risk is Assessed in the Spiral Lifecycle
The spiral model is a risk-driven model, meaning that the overall success of the project is determined on risks being analysed accurately. Risks are possible conditions and events that prevent the development team from achieving the aims of the software. The primary task for a development team is to establish the possible risks and list them according to their importance. The next step is to determine potential methods that can help to overcome the risks before they start to cause issues to the development process. Evaluation of these methods can cause changes to the next stages of the spiral lifecycle as development plans may have to change to compensate for these risks.

### The V-Model
#### What is the V-Model?
The V-Model is very much like the waterfall model in nature, as the V-Model uses a specified series of linear stages, to be completed one at a time until the project is fully complete. For this reason, the model is considered to be a sequential lifecycle, it is also known as the validation and verification model. Validation ensures that the product is being developed for all the user needs specified, and verification ensures that the product is following all the design specifications. The objectives of the model are to minimize project risks and to guarantee that the product will be of high quality.

The stages of the v-model are as follows:
* Requirements: Before development is started, requirements are planned, describing what user needs have to be fulfilled by the finished product. During this design phase, corresponding tests are also designed to be implemented later during the testing stages, the tests designed are called acceptance tests.
* The Architectural Design: This is the stage where the architecture of the software is designed and the components within the software are built and the relationships between the components are established.  The system tests are also planned and correspond to this stage.
*	The High-Level Design: This stage involves breaking down the system into subsystems with identified purposes. The integration tests are then planned out, which are tests that involve combining the all subsystems and testing the product as a whole.
*	The Detailed Design: This stage is where the implementation of each component is specified. The design is broken down into data structures, algorithm used and the unit tests are designed, which are the tests for the actual source code of the product.
*	Coding: This is treated as the final stage of model, where each component of the software is coded and tested to verify the integrity of the product.
### Advantages of the V-Model
*	Ensures Quality of the Product: The emphasis of verification and validation of the product in the early stages of development, means that the product is ensured to fulfil all user needs and ensures that the design of the product is accurate and fully complete
*	Suited for Restricted Projects: Due to the linear design of the model, projects where the length and scope are well-defined and the design specifications are clear the V-model can be a useful method.
*	Ideal for Time Management: This model is also well-suited for projects that are kept to a strict schedule, with key milestone dates and a concrete deadline. This is because the sequential stages of the model can be prepared for, with the development team creating a time line for each stage of the whole model. This does not mean that each milestone will be met on time, but the strict structure of the model enforces the need to keep a tight schedule.
### Disadvantages of the V-Model
*	Lacks Adaptability: Like the waterfall model, the V-Model struggles with adapting to any necessary changes during development. If an issue with the initial design is overlooked and only found later on in the lifecycle, it would present a huge setback for the development team as they would have to revert to the initial design stage and go through all the stages again, wasting the time previously spent on the project.
*	Not Suited for Lengthy Projects: As the V-model is completely linear, projects cannot be easily altered once development has started. Therefore, the model is poorly suited for long-term projects that will require maintenance when the product is released.
