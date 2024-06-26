# Manual-Testing-Projects

This project contains a list of details regarding manual testing that I have learnt throughout my career and my post graudation in Software Quality Assurance and Test Engineering.

#Basics of Testing

1. Software Development Lifecycle

   Participated for QA activity in all the steps of the SDLC
   
   1️⃣ Requirement Analysis <br>
   Discussion with BA/ PO regarding the requirement, discussing scenarios that would come up if a change is implemented, jotting down impacted areas, technical architecture of the new     changes involved. Describe what the software application/system needs to be to able to do. Mainly writeen in a way that is understood by everyone in the team. During this discussion we should also describe what the software application needs to be able to do but in more granularity. Technical discussions should take place at this stage.  <br>
   ✔ Participated in Requirement analysis for portguese news web page created using word press, mobile web applications, Shopify applications in Shine Dezign Infonet Pvt. Ltd. <br>
   ✔ Participated in the Requirement analysis for new features that were introduced for the HRIS system, which included multiple modules. Requirement analysis for the  introduction of triggers and change requests, handled the  requiremet analysis interdependent modules in CatalystOne Info. Solutions Pvt. Ltd. <br>
   ✔ Participated in the requirement analysis for major releases which included Financial selector screen, Fraud Monitoring, implementation of Data model and partner integrations. Verified 
     the analysis and prepared edge cases accordingly in Spring Financial. <br>
<br><br>

   2️⃣ Planning
   Discussing development plan, test plan. Responsible for planning the testing that will be done during the sprint for the specific feature planned for deployment. This also include time taken for the test activirty, number of test cases required to be developed, executed, created, peer-reviewed, turn-around time for fixing defects. <br>
   🔼 Establishing the scope- Number of use cases, requirement specifications, modules, classes, functions, methods to be tested, number of platforms to test the requirement on, anticipated number of defects that could be found and keeping extra bandwidth while providing estimations. Lastly mentioning the environments to test and devices.

   ✔ Created test plans for Kanaban team in Shine Design focusing on the new features, the Test plan was created using MS Excel, consisting of scenarios to be tested (higher level), hours spent on the activity and tracking the overall advancement of the testing process, environment in which the change is to be tested. <br>
   ✔ In CatalystOne a defined Test Plan was created based on Estimation techniques- Work Break Down Structure, it was important to focus on the Risk-Based Priority Driven Testing and Business critical flows as part of the SIT Team, therefore the Test Plan for any feature focused on business critical flows and the Risky areas, once those were handled, a top-down approach was planned for other areas. The hours spent are inclusive of testing on staging environment (integrated environment) and sandbox environment. The Test plan and test cases were created in TestLink. <br>
   ✔ In Spring Financial, due to the urgency of requirements the Test Plans are created as Phase Test Plan. i.e. Focusing on all test items included in the Sprint. The test planning also included creation of test cases and execution in the feature branch, release branch and the master branch. Test cases are created using Qase. <br>

   In short, during the test planning I have focused on Analysing the code/ requirement/ user Stories ⏭️ Develop the Test Strategy ⏭️ Develop Test Plan and Test Case(s) ⏭️ Execute the Test Case ⏭️ Create and Publish Reports


<br><br>

   3️⃣ Designing
   In the Designing phase imphasis has been to identify aspects of the design that might cause problems, for this it is crucial for me to understand how the current design works and how adding something new might hamper, affect the existing flow. This allows to prepare detailed regression test cases.<br>
   ✔ For Shine Deizign the mocks were sent by the business analysts after discussion with the PO and I was supposed to provide my analysis of the design on different devices. I would ask for the most used devices to prepare my analysis according, there was usually not a large scope of change in these discussions <br>
  ✔ For CatalystOne I was included in the design phase during the implementation of microservices from their monolithic architecture, deriving how the services would work, preparing the contanerised environment. This discussion also included implementation of technical architectural changes and not just UI. There was a UI change for a new feature, I was included in the design meetings and provided scenarios to keep in mind for the Scandanavian alphabets.
   ✔ For Spring Financial, we have a Design team that sends the Figma after they have been approved, once the Figmas are approved a round of discussion is held regarding the User experience and any change where we can enahce the UI/ UX. Once discussed changes are implemented and the designs are changed and sent for Final round of approval. <br><br>

   4️⃣ Implementation
  ✔  I have taken up various discussions with the Salesforce developer regarding Implementation of new changes and how we can enhance the change for everyone involved.  <br><br>

  5️⃣ Testing
  The main job starts
  ✔ Performing unit testing, component testing on the feature branch <br>
  ✔ Experienced in Regression Testing, preparing detailed regression suites and maintaining them with every iteration<br>
  ✔ Experienced in Sanity and Smoke Test using CI/ CD pipelines
  ✔ Running automated suites for regression using Typescript
  ✔API testing using Postman



  <br><br>
  <h3>Projects I have worked on</h3> <br>
   ✔ Spring Financial <br>
   1. Auto-Underwriter Model <br>
   One of the first projects assigned to me in the QA team of two, I was supposed to analyze that the model decision was working as expected and sending the results after verifying the banking file of the customer to the BE to store the payload in the databse table and finally move to the CRM (salesforce), This testing also included verifying the flow from S3 to snowflake (using Papertrail). Eventually I have become the core QA to handle all the changes and upgrades made from version 1 to version to for the Data Science Team. <br>
   2. Fraud Monitoring <br>
   For ensuring the Underwriting team was handling accurate customer data, we developed a logic in the Backend and Front end. In the application, customers are asked to enter banking details and photo ID, we would map the customers name of the ID, banking data and send it to the Fraud Monitoring section on Salesforce <br>
   3. Marketing Parameters <br>
   Ensuring that Growth department is able to fund the partners and create funnels for leads gathered from different opportunities, we implemented logic to track the marketing parameters, testing included verifying flow from different resources <br>
   4. State machines for partner integration <br>
   We implemented a logic where the state machines in AWS would be triggered when any partner would be called and on another action, I had to ensure that testing focused on correct state machine triggering for all partners. <br>
   5. Financial Selector Screen <br>
   One of the main changes in applciation flow was introduction of a new financial screen, where testing focused on the integration, Front end and backend calls, response, requests and ensuring correct banking files were being save din the database and the CRM, the project was a success with zero bugs in production. <br>
   6. Partner Integration <br>
   Recently handled a new partner integration from scratch and led the QA forefront for all activities, ensured accurate data being passed and the integration between Salesforce, Integration Module and Loan Module. Successfully released this product with feature flag toggled off ensuring regression testing done to perfection with no impact on the current flow. Once the toggled was turnt on successfully had a seamless release.<br>
   7. Odoo Integration
   Currently working on Odoo being the new CRM, buiding test strategies, issue trackers, test cases and scnearios from scratch and communivation updated to the PO.
