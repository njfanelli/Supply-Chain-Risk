<h2><strong>Overview</strong></h2>
<p>Supply Chain Risk Management is common challenge for organizations and as many fight to keep their supply chain under control we often look for more effective ways to assess risk being introduced into the environment.&nbsp; To address this challenge the Supply Chain Risk Assessment (SCRA) tool was created to assist organizations in identifying, evaluating and reporting risk within the supply chain process.&nbsp;</p>
<p>&nbsp;</p>
<p>SCRA was developed with the following goals in mind:</p>
<ul>
<li>The foundation of the tool must be based on a common framework.</li>
<li>There must be a cross walk for the questions defined to other standards/regulations.</li>
<li>Remove the ambiguity in vendor responses.</li>
<li>Eliminate the subjectivity in the scoring process.</li>
<li>Provide an efficient way to identify gaps in the vendor response.</li>
<li>Map assessments results to the tolerance levels defined by leadership.</li>
<li>Offer an Executive Summary of the assessment.</li>
<li>The tool must be macro/script free.</li>
</ul>
<hr />
<p>&nbsp;</p>
<h2>Assessment Process</h2>
<p>Before we jump into the tool lets quick walk through the assessment process (your process may be different):</p>
<ol>
<li>The initial request for new or change of technology is submitted by the customers Application Team/Business Unit, once complete the Technology Assessment Questionnaire is routed to the vendor.</li>
<li>The vendor will complete the multiple-choice questionnaire and return the results back to the customer.</li>
<li>The customers Security Team will assess the vendors response and summarize the results within the tab labeled &ldquo;Assessment Summary&rdquo;, this report will highlight the data value being handled by the solution, the risk exposure (impact/likelihood of a threat event) and whether the security controls implemented by the vendor meet the risk appetite defined by customers leadership.</li>
<li>The customers Security Team will present their findings to the customers Application Team/Business Unit, any gaps identified and/or guidance as to how the solution should be deployed within with the environment will be addressed at this time.</li>
<li>Results of the assessment are formally documented with the central Governance, Risk &amp; Compliance (GRC) tool. Any gap identified in the prior step will be added to the risk register, prioritized by the Security Team and assigned to the Application Team/Business Unit for remediation.&nbsp; If the assessment results fall within the tolerable levels of the organization the solution may at this point advance to Step 8 in the process (Approved for Use).&nbsp; NOTE: it is suggested that the customers Application Team still work on developing a plan to address any gap in the long-term strategy of the solution.&nbsp; If the assessment results however fall outside the tolerable levels of the organization the solution must move to Step 6 in the process (Remediation Phase) as it is not approved for use until gaps are addressed and risk is driven to an acceptable level.</li>
<li>The customers Application Team/Business Unit will establish a remediation plan to address the gaps identified (working with the vendor if needed). If the gaps are remediated and risk is reduced to a tolerable level the risk register is updated within the GRC tool and the request is moved to Step 8 of the process (Approved for Use).&nbsp; If the gaps cannot be remediated to an accepted level (due to financial constraints, technology challenges, etc.) and the solution is still critical to the environment the Application Team/Business Unit will need to prepare a business case to be reviewed and the inherit risk accepted by the customers Leadership team before it can be advanced to Step 8.&nbsp;&nbsp;</li>
<li>The customers Leadership team will review the business case documented and decide whether to accept the residual risk which would advance the assessment process to Step 8 (Approved for Use) or reject the request which would halt any further movement of the project.</li>
<li>The solution is approved for use, the customers Security team is to remain involved during the planning, development, testing and implementation phases to ensure no additional risk is introduced.</li>
<li>Once the solution has been implemented it is to be re-assessed/evaluated on a regular basis, the customers Security team will create a reminder to trigger an event at the time defined within organizations policy.</li>
</ol>
<p>&nbsp;<img src="https://github.com/njfanelli/Supply-Chain-Risk/blob/main/Image-Workflow.png" alt="" /><img src="https://github.com/njfanelli/Supply-Chain-Risk/blob/main/Image-Workflow.png" alt="" /></p>
<hr />
<h2>Assess Questionnaire</h2>
<p>This workbook contains the following worksheets (tabs):</p>
<ul>
<li><strong>Vendor Questionnaire</strong> &ndash; This is one of the primary tabs within the workbook and will be used to collect information from your internal teams as well vendor direct. Ideally, this should be the only tab visible by default, no one but the security practitioner needs access to the other tabs noted below.
<ul>
<li>This worksheet is broken up into three sections.
<ul>
<li>The <u>first</u> is to be completed by your internal team and includes several sub-sections:
<ul>
<li><strong>Technology Request</strong> &ndash; The section covers your basic information, Solution Name, Internal Project #, Department/Cost Center.</li>
<li><strong>Point of Contacts</strong> &ndash; This section will be used to keep record of the key players for the project.</li>
<li><strong>Solution Profile</strong> &ndash; This section helps us understand the type of technology being presented (is it new or existing tech being upgraded), we&rsquo;re also looking to capture the target audience and this is a required field that will be used later to determine our overall Impact level.</li>
<li><strong>Data Classification</strong> &ndash; As with any solution it&rsquo;s important to capture the type of data that will be stored/processed by the technology, in this section we ask the requestor to identify the Information Types and desired Protection &amp; Availability Levels. I&rsquo;ve provided a legend (directly below this section) to aid in making your selections.&nbsp; NOTE: It is required that at least one Type of data be defined and included expected Protection &amp; Availability levels, this information will assist in determining our Impact level.</li>
</ul>
</li>
<li>The <u>second</u> section is dedicated to the vendor and contains two primary sections:
<ul>
<li><strong>Vendor Profile</strong> &ndash; This section is available for any general questions about the vendor or the service/product being assessed. NOTE: the responses to these questions do not currently have an impact on the overall scoring of the assessment.</li>
<li><strong>Technical Assessment</strong> &ndash; This section contains a total of 104 multiple choice questions that are based on the Center of Internet Security (CIS) Top 20. All questions require a response and the vendor has the option to add comments (if desired).&nbsp; The questions, along with other content that I&rsquo;ll reference later, is directly pulled from the &ldquo;Technology Master&rdquo; tab so if any changes are needed those changes should be made within the Master sheet NOT the Vendor Questionnaire.</li>
</ul>
</li>
<li>The <u>third</u> and final section is to be hidden by default but can be used as a reference for practitioners as it provides the Impact and Likelihood for each of the 5 Attack Scenarios identified.</li>
</ul>
</li>
</ul>
</li>
</ul>
<p style="text-align: center;"><em>Screenshot of the Vendor Questionnaire tab</em></p>
<p>&nbsp;&nbsp;</p>
<ul>
<li><strong>Assessment Results</strong> &ndash; Based on the responses received by the Vendor &amp; Customers Application Team, this tab will summarize the following for the solution:
<ul>
<li>Data Value (Low, Medium, High)</li>
<li>Risk Exposure (Low, Medium, High)</li>
<li>Appetite Level (Unacceptable, Tolerable, Acceptable)</li>
<li>Summary of the Security Controls Assessed</li>
<li>Breakdown of Responses by Control Area</li>
<li>Gaps Identified in the Vendors Response</li>
<li>Potential Gaps where Customer is Responsible for Control Implementation</li>
</ul>
</li>
</ul>
<p style="text-align: center;"><em>Screenshot of the Assessment Results tab</em></p>
<p>&nbsp;</p>
<ul>
<li><strong>Guide</strong> &ndash; Provides on overview on this tool as well as the expected process follow (which your welcome to modify).</li>
<li><strong>Revisions </strong>&ndash; Will display the change history of the tool as it matures.</li>
</ul>
<p style="text-align: center;"><em>Screenshot of the Revisions Tab</em></p>
<p>&nbsp;</p>
<ul>
<li><strong>Technology Master</strong> &ndash; This tab is critical to the overall workbook as it contains the total population of questions within the tool and it outlines how those questions are mapped back to various attributes, any changes to the questions (or attributes linked to these questions) should be made within this sheet as it will self-correct the Vendor Questionnaire tab.
<ul>
<li><u>Details on the columns defined and their purpose:</u>
<ul>
<li><strong>Category </strong>&ndash; CIS Controls V7 separates the controls into three distinct categories: basic, foundational, and organizational.
<ul>
<li><strong>Basic </strong>&ndash; key controls which should be implemented in every organization for essential cyber defense readiness.</li>
<li><strong>Foundational </strong>&ndash; these technical best practices provide clear security benefits and are a smart move for any organization to implement.</li>
<li><strong>Organizational </strong>&ndash; are more focused on people and processes involved in cybersecurity.</li>
</ul>
</li>
<li><strong>Control # </strong>- This column is linked to the actual question number that will appear in the Vendor Questionnaire tab.</li>
<li><strong>CIS Actual # </strong>- This aligns to the actual CIS sub-control number (wording modified slightly) for each question.</li>
<li><strong>Control Focus </strong>&ndash; CIS Controls V7 is made up of 20 control areas and each question is mapped to a control, they are:
<ol>
<li>Inventory of Authorized and Unauthorized Devices</li>
<li>Inventory of Authorized and Unauthorized Software</li>
<li>Continuous Vulnerability Assessment and Remediation</li>
<li>Controlled Use of Administrative Privileges</li>
<li>Secure Configurations for Hardware and Software on Mobile Devices, Laptops, Workstations, and Servers</li>
<li>Maintenance, Monitoring, and Analysis of Audit Logs</li>
<li>Email and Web Browser Protections</li>
<li>Malware Defenses</li>
<li>Limitation and Control of Network Ports, Protocols, and Services</li>
<li>Data Recovery Capabilities</li>
<li>Secure Configurations for Network Devices such as Firewalls, Routers, and Switches</li>
<li>Boundary Defense</li>
<li>Data Protection</li>
<li>Controlled Access Based on the Need to Know</li>
<li>Wireless Access Control</li>
<li>Account Monitoring and Control</li>
<li>Implement a Security Awareness and Training Program</li>
<li>Application Software Security</li>
<li>Incident Response and Management</li>
<li>Penetration Tests and Red Team Exercises</li>
</ol>
</li>
</ul>
</li>
</ul>
</li>
</ul>
<ul>
<li><strong>Security Function </strong>&ndash; The CIS framework is based on five primary pillars Identify, Detect, Protect, Respond and Recover. Each question is mapped back to one of these areas.</li>
<li><strong>Control Question </strong>&ndash; This column contains the actual question that would appear on the Vendor Questionnaire tab.</li>
<li><strong>Data Value (High, Medium, Low) </strong>&ndash; The questions documented may be viewed differently by an organization based on the type of data being handled or by impacted audience, with that said this tool was built to allow a practitioner to tag which questions they feel are REQUIRED &amp; RECOMMEND.
<ul>
<li><u>REQUIRED EXPLAINED:</u> if this option is selected it is expected that the vendor have the necessary control in place (answer YES) should they answer NO then points will be deducted from their overall score and enough negative points may push the solution outside the tolerance allowed by the organization.&nbsp; NOTE: by answering Customer Responsibility will neither hurt or help the vendor but it does provide awareness to the customer that they&rsquo;re on the hook for addressing said control.</li>
<li><u>RECOMMEND EXPLAINED:</u> if this option is selected it means a response of YES by the vendor will be viewed as a compensating control and depending on the Security Function of that question additional points will be added to the overall assessment.&nbsp; The response of anything else will neither hurt nor harm the vendor.</li>
</ul>
</li>
<li><strong>Response Options </strong>&ndash; The goal when building this questionnaire out was to establish an effective yet efficient way to assess responses, to do this all questions were configured with a multiple-choice response. The three options are YES, NO and CUSTOMER RESPONSIBILITY, details below:
<ul>
<li>"YES" - the VENDOR acknowledges responsibility for the control/process AND it is included within the service offering.</li>
<li>"NO" - the VENDOR acknowledges responsibility for the control/process AND it is NOT included within the service offering OR does not meet the criteria defined.</li>
<li>"CUSTOMER RESPONSIBILITY" - You the vendor are providing a commercially available solution and its owner's responsibility to implement said control/process.</li>
</ul>
</li>
<li><strong>NIST Policy Reference </strong>&ndash; Each of the applicable control questions were mapped back to a NIST 800-53 control/s. Details on how this was accomplished can be found under the NIST MAP tab.</li>
<li><strong>HIPAA Reference </strong>&ndash; Each of the applicable control questions were mapped back to a HIPAA Regulation. Details on how this was accomplished can be found under the HIPAA MAP tab.</li>
<li><strong>PCI Reference </strong>&ndash; Each of the applicable control questions were mapped back to a PCI Control area. Details on how this was accomplished can be found under the PCI MAP tab.</li>
<li><strong>Risk Statement </strong>&ndash; A pre-canned risk statement has been documented for each control question. This statement can be modified by the practitioner and will display within the Assessment Results tab for any non-conforming control identified.</li>
<li><strong>Comments </strong>&ndash; This column has no bearing on the overall outcome of the solution, it can be used to record notes regarding any of the questions documented. This may be helpful if you have multiple practitioners collaborating within the tool.</li>
<li><strong>Control Guidance </strong>&ndash; This column is a place marker for a future add-on, as gaps are identified the goal here is to provide guidance on a potential solution that could be implemented to address the issue.</li>
<li><strong>Attack Summary Mapping </strong>&ndash; There are five attack scenarios that are defined and within scope for every assessment (see below). Each of the 104 questions defined within the Technical Assessment have been mapped back to <u>one</u> Attack scenario, while it&rsquo;s possible that a question may be attributed to multiple scenarios for the intent of this tool the practitioner must choose only one (this can be done by modifying Column Q of this worksheet).
<ul>
<li>The five scenarios are:
<ul>
<li>Cyber Attack</li>
<li>Unauthorized Access to Systems or Data</li>
<li>Human Error (User, Maintenance, Operation)</li>
<li>System Failure (Hardware, Software, Communication, Power, etc.)</li>
<li>Environmental Disaster (Fire, Water, Natural Disaster, Terrorism)</li>
</ul>
</li>
<li>NOTE: The Attack scenarios results can be found (and overridden) under the Vendor Questionnaire tab, you&rsquo;ll need to scroll down and unhide Rows 186-206 within the sheet.&nbsp; Presently the Impact level for each scenario will be the same as this is determined by <em>Data Value * Audience</em>, the assumption was made that those two attributes will not change as it is challenged by each scenario. &nbsp;This again can be manually overridden by the practitioner (if needed).</li>
</ul>
</li>
</ul>
<p style="text-align: center;"><em>Screenshot of the Technology Master tab</em></p>
<p>&nbsp;</p>
<p style="text-align: center;"><em>Screenshot of the Attack Summary table under the Vendor Questionnaire tab</em></p>
<p>&nbsp;</p>
<ul>
<li><strong>Risk Calc</strong> &ndash; This tab is also critical to the overall workbook as the information that is defined within here will determine the grading scale for how the solution is assessed. The Risk Calc worksheet is broken up into three sections&hellip; Data Value Calculation, Risk Exposure Calculation and Risk Appetite Calculation, each are explained in further detail below.&nbsp; NOTE: Throughout this worksheet practitioners are encouraged to work with their leadership to ensure the values defined in RED align with views and expectations of the organization.</li>
<li><strong>Data Value </strong>&ndash; (<em>Protection * Availability). </em>If there are multiple data types identified for the solution with various protection and/or availability levels the tool will calculate and use the greatest value (see Final Conclusion in this section).
<ul>
<li><strong>Protection </strong>is broken down into four categories:
<ul>
<li>P1 - Public</li>
<li>P2 - Internal Data</li>
<li>P3 - Sensitive</li>
<li>P4 - Highly Sensitive</li>
</ul>
</li>
<li><strong>Availability</strong> is broken into four categories:
<ul>
<li>A1 - Minimal</li>
<li>A2 - Low</li>
<li>A3 - Moderate</li>
<li>A4 - High</li>
</ul>
</li>
</ul>
</li>
<li><strong>Risk Exposure &ndash; </strong><em>(Impact * Likelihood).</em> Obviously, each attack scenario will display a different level of risk, the table to the far right in this section (labeled Final Conclusion) will run a calculation of all scenarios and determine the greatest risk area and use that in our report section.
<ul>
<li>First to calculate <strong>Impact</strong> we multiply <em>(Target Audience * Data Value)</em> which will return a result of Insignificant, Moderate or Significant.
<ol>
<li><strong>Data Value</strong> is pulled from the prior section.</li>
<li><strong>Target Audience</strong> is broken into five categories:
<ul>
<li>Small group of users</li>
<li>Single department</li>
<li>Campus</li>
<li>Entire organization</li>
<li>Patients/General Public</li>
</ul>
</li>
</ol>
</li>
<li>Next we need to calculate our Likelihood, to get this information we sum up the responses of all questions by attack scenario. The first part in this is to calculate the compliance percentage of all questions identified as REQUIRED, we then we credit the vendor additional points for any RECOMMEND control (aka Compensating Control) to come up with our final percentage.&nbsp; Listed below this area is a table that defines our thresholds for what is viewed as <strong>Almost Certain</strong>, <strong>Possible</strong> and <strong>Rare</strong>.</li>
<li>Finally to calculate Risk Exposure we multiply <em>(Impact * Likelihood</em>).</li>
</ul>
</li>
<li><strong>Risk Appetite &ndash;</strong> <em>(Data Value * Risk Exposure)</em>. In the final section of this worksheet the practitioner (working with leadership) will define the tolerance levels of the organization, once that has been established there will be a clear path in how we disposition the assessment.
<ul>
<li>There three levels are:
<ul>
<li><strong>UNACCEPTABLE </strong>- Risk cannot be justified except in extraordinary circumstances.</li>
<li><strong>TOLERABLE </strong>- Residual risk is tolerable only if further risk reduction is impracticable. Extraordinary cost and effort would be required and would only marginally reduce the risk.</li>
<li><strong>ACCEPTABLE </strong>- Risks are negligible or so small that can be managed by routine procedures and no additional risk measures are needed.</li>
</ul>
</li>
</ul>
</li>
</ul>
<p style="text-align: center;"><em>Screenshot of the Risk Calc tab</em></p>
<p>&nbsp;</p>
<ul>
<li><strong>Customer Gap Calc</strong> &ndash; This tab is calculating the questions where the vendor has responded CUSTOMER RESPONSIBILTY to a question, all the CUSTOMER RESPONSIBILTY&rsquo;s are filtered, sorted then presented into the Assessment Result tab under the &ldquo;Controls Customer is Responsible in addressing&rdquo;.</li>
</ul>
<p style="text-align: center;"><em>Screenshot of the Customer Gap Calc tab</em></p>
<p>&nbsp;</p>
<ul>
<li><strong>Vendor Gap Calc</strong> &ndash; This tab is calculating the questions where the vendor has responded NO to a question, all the NO&rsquo;s are filtered, sorted then presented into the Assessment Result tab under the &ldquo;Controls Gaps Identified in Vendor Response&rdquo;.</li>
</ul>
<p>&nbsp;</p>
<p style="text-align: center;"><em>Screenshot of the Vendor Gap Calc tab</em></p>
<p>&nbsp;</p>
<p>Additional Resources/Tabs within this workbook:</p>
<ul>
<li><strong>Why CIS Top 20</strong> &ndash; This tab provides some basic information on CIS Top 20 and its importance.</li>
<li><strong>NIST Map</strong> &ndash; An aggregate of resources was used to build out this tab.</li>
<li><strong>HIPAA Map</strong> &ndash; An aggregate of resources was used to build out this tab.</li>
<li><strong>PCI Map</strong> - An aggregate of resources was used to build out this tab.</li>
</ul>
<p>&nbsp;</p>
<p style="text-align: center;">Special thanks to the following entities (see below), content from their website was used as an aid to build this questionnaire:</p>
<p style="text-align: center;">Cisecurity.org, AuditScripts.com, HHS.gov, Cisa.gov, and the Security Team at UC Irvine.</p>
