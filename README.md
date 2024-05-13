# HR ANALYTICS PROJECT USING POWER BI 
<h1>EMPLOYEE PRESENCE INSIGHTS</h1>

<H2>💼 The Task:  </H2>
The task was to develop an interactive Power BI dashboard aimed at streamlining HR operations for Pinali Mandalia, who serves as the HR lead at AtliQ Technologies. This dynamic dashboard is designed to uncover actionable insights by visually presenting trends and patterns within the data, empowering informed, data-driven decision-making processes.

🚀 <B>Note:</B> The dataset is provided by CodeBasics, where the data is for 3 months i.e. April, May, and June of 2022. 

<H2>Requirements:</H2> 
The specifications outlined by the HR manager are as follows:
<OL>
<LI> Working preference of people between working from home(WFH) and working from office(WFO)</LI>
<LI> The percentage of overall sick leave to understand and monitor employee wellness</LI>
<LI> Determining the percentage of employees present during a given week or month allows for a clear understanding of workforce utilization and can inform decision-making regarding resource allocation, scheduling, and operational planning</LI>
<LI> Identifying the days with the highest WFH (Work From Home) rates enables strategic scheduling of office maintenance and infrastructure work, optimizing resource allocation</LI>
<LI> Pinpointing the day of the week with the highest attendance allows for strategic event planning to ensure maximum participation and engagement</LI>
<LI> Developing a rotational or hybrid work arrangement where employees alternate between office and remote work, presents an opportunity to reduce rental expenses while maintaining productivity and flexibility.</LI>
</OL>

<H2>📈 Key Metrics:</H2>
The following KPIs were created using DAX:
<OL>
<LI>📆 Employee Presence %: We calculated and visualized the overall attendance percentage, providing a clear view of workforce presence.</LI>
<LI>💼 WFH(Work from Home) Count and %: In today's dynamic work environment, we evaluated the WFH % to understand the flexible work culture's impact.</LI>
<LI>🤒 SL(Sick Leave) Count and %: Tracking sick leave percentages is vital for employee health and organizational planning.</LI>
</OL>
<H2>📊 Visualization:</H2>
We brought these metrics to life using Power BI. We designed a dynamic dashboard featuring line charts that illustrated how these statistics changed over time. The line charts allowed us to identify trends, patterns, and potential areas for improvement.

<H2>📌 Steps Followed: </H2>

<OL>
<LI><B> Data Cleaning and Data Transformation using Power Query:</B> Combine the data from multiple Excel sheets that have different column names into one usuable format, combine all the dates in multiple columns into one column,
created custom columns etc.</LI>
<LI><B> Dynamic Data Transformation:</B> Transforming data in dynamic way so that it works with new data as well.</LI>
<LI><B> Creating Metrics using DAX:</B> Build KPIs- to build key performance indicators like Presence %, WFH %, SL % using different formulas.</LI>
<LI><B>Formulas used: </B>CALCULATE function in DAX, SWITCH, DIVIDE, COUNT, Sum etc.</LI>
<LI><B>Charts:</B> Used area chart and trend line to show the insights clearly.</LI>
</OL>
<h2>📈 Key Insights drawn:</h2>
Starting from April to June 2022,
<ol>  
<li>✨The Presence % by month is declining</li>
<li>✨WFH(Work from Home) % of working people is increasing</li>
<li>✨SL %(Sick Leave) is a little bit increasing</li>
<li>✨Most of the employees prefer WFH on Friday and Thursday</li>
<li>✨Most of the employees are present on Monday and Tuesday</li>
</ol>

<h2>🌐 Impact and Next Steps:</h2>
These revelations aren't mere figures; they're the cornerstone of well-informed choices. The following steps are also embedded in this Power BI project. 
<ul>
<li>📈🔍Sending alerts</li>
<li>📈🔍Automatic data refresh</li>
<li>📈🔍Setting security levels for data</li>
</ul>

<B>Note:</B> Based on the feedback from the HR manager and other stakeholders, this particular MVP(Minimal Viable Product) can be enhanced in the next version of the dashboards.

<h2>📌 Significance:</h2>
Effective HR analytics is crucial for businesses looking to optimize their workforce, enhance productivity, and create a healthy work environment. By harnessing data and creating visually engaging reports, we can make informed decisions that benefit both employees and the organization.

<h2>💡 Lessons Learned:</h2>
<ol>
  <li>✨Data cleansing and preparation are the foundational steps for analytics.</li>
  <li>✨Visual storytelling is essential for making data understandable and actionable.</li>
  <li>✨Power BI is a potent tool for creating interactive, data-driven dashboards.</li>
</ol>
