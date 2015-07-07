LINK FOR WORKING DESIGN POOL URL IS AS FOLLOWS:
http://adspool1.yakshna.com

AGILE DELIVERY SERVICES FOR DESIGN POOL-1 BY
YAKSHNA SOLUTIONS, INC. (YSI)
07/06/2015


I. DESIGN APPROACH FOR DESIGN POOL PROTOTYPE

YSI identified Product Manager who is cerified scrum master to lead on Agile delivery services.He was pulled from  current working project to lead ADS prototype design. Product Manager allocated the resources, costing for the design prototype.  He initiated 30 minutes stand up meeting everyday for 4 days. He identified the team every day for 4 days. He identified the labor categories  Visual Designer and Front end web developer to work on design pool prototype.Team has expertise in open source technologies like HTML,CSS, jQuery and AJAX. Team discussed the RFQ requirements and the other related documents .Team did review of Q&A response documents provided by the agency and did brainstorming session. As a team identified the needs of the patients and healthcare providers. After couple of discussions,team came up with High Level Requirement document.Refer document for requirements YSI_ADS_System_Requirement_Specification_Pool_1 in the Repository. And team identified the data set Device to be shown on user interface which is taken from www.open.fda.gov website.Data elements are discussed in the meeting which need to be displayed on interface from Device dataset.

Design Phase:Team started putting up the high level design document to prepare the Design pool prototype.Open source Technologies are identified HTML5, CSS 3, jQuery and Bootstrap for responsive design. HTML page had been designed by Visual designer to display the Devices details on the static user interface and design is made responsive to support multiple devices like mobile devices,desktops,laptops etc.

Tortoise SVN tool is used for configuration management and maintaining the iterations of the code. Product manager reviewed the design and gave the review comments which were followed by team. couple of iterations are made to the design after incorporation of review comments.

Testing Phase : After the completion of design, testing phase was initiated by the team. Running of test cases was maintained in Tool called Jira.Test cases was written and test cycle executed and defect log generated. Refer test documents in the repository for more details Test Plan,Test case report,Defect Report : 
YSI_ADS_System_Test_Report_Design_Pool_1,
YSI_ADS_System_Defect Report_Design_Pool_1,
YSI_ADS_System_TestPlan_Design_Pool_1.

II.  HOW TO INSTALL DESIGN POOL PROTOTYPE ON WINDOWS PLATFORM

1. Create an application pool in the IIS interface from application pools section
2. In the add application pool dialog box give any name and select any .net framework since the source code will work in any framework
3. Select integrated pipeline mode and click ok to create the application pool
4. Give permission to the IIS identity which is running the application pool to the source code folder
5. Create a website in IIS interface by right clicking in the sites node
6. In the add website dialog box provide site name, root path to the source files, host header names if any
7. Select the application pool name from the step 3
8. Select the newly created website name and from the right pane select Default Document
9. In the default document list check and make sure index.html is present
10. Access the domain and check and make sure the website is giving the index.html as the response.

III. HOW TO INSTALL DESIGN POOL PROTOTYPE ON LINUX PLATFORM
Refer document in the repository :YSI_ADS_Installation_Guide_Design_Pool_1

IV. MINIMUM SYSTEM REQUIREMENTS 

¥ Windows or Linux OS, Internet Connectivity
¥ Minimum 64 MB of RAM
¥ Internet Explorer 9.0 or above, Chrome 38 or above and Firefox 35 or above, Safari 5 or above

V. KNOWN RISKS

Data will be shown to user fetched from open.fda.gov API. If the API fails for any reason then user interface will not show up the data. Prototype has a dependency on the API. Also the site is not developed with Section 508 compliant due to the time constraint.
