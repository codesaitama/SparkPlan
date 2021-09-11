<h1 style="align: center">Spark Design, Implementation and Deployment</h1>

# Introduction

<h5>Spark Dashboard is meant to manage members/customers and their club information. It's also supposed to keep track of transactions and general activities on loans and savings within clubs etc.</h5>

<h5>The purpose of the <i>Software Development Plan</i> is to gather all information necessary to control the project. It describes the approach to the plan generated and used by managers to direct the development effort.</h5>
<br/>

<p>The following people use the Software Development Plan</p>

<h5>The <strong>project manager</strong> uses it to plan the project schedule and resource needs, and to track progress against the schedule. </h5>
<h5><strong>Project team members</strong> use it to understand what they need to do, when they need to do it, and what other activities they are dependent upon. </h5>
<br/>

# Scope

<h5><li>View all member/club information.</li></h5>

<h5><li>Dispense loans from the dashboard.</li></h5>

<h5><li>View all delinquent and default users.</li></h5>

<h5><li>Manage the overall portfolio of loans and savings.</li></h5>
<br/>

# Design Plan

Development Environment Setup
-----------------------------

<h5>Effective Development Environment Setup implementation in this case means specification of all details or algorithms, design, programming, testing, deployment, and maintenance. </h5>

<h5>Setting up an effective development environment in advance is very rare. Development environment setup, as well as using of proper tools, is mostly left to the particular developer. Although many IT companies are aware of the need to use an effective development environment and standard set of tools, very seldom does this awareness assist in the choosing of an Integrated Development Environment (IDE) framework and target database software.</h5>
<br/>

<p>Servers to choose from</p>
<h5>
<li>Linux Servers. Eg: Ubuntu 18, 20</li>
<li>Windows IIS Server</li>
<li>Google Cloud Platform</li>
<li>AWS</li></h5>
<br/>

<p>Libraries/Frameworks [Language] to choose from for frontend development putting performance and code refactorability in mind.</p>
<h5>
<li>ReactJS/NextJS for web app (NextJS allows server-side rendering that helps with SEO) [JS]</li>
<li>React Native for IOS/Android [JS]</li>
<li>Flutter for IOS/Android [Dart]</li></h5>
<br/>

<p>Libraries/Frameworks [Language] to choose from for backend development</p>
<h5>
<li>NodeJS & Express [JS]</li>
<li>ASP.NET Core [C#]</li>
<li>Flask [Python]</li>
<li>Django [Python]</li></h5>
<br/>

<p>Database technologies to choose from data management</p>
<h5>
<li>Microsoft SQL Server </li>
<li>MySQL Server</li>
<li>PostgreSQL Server</li>
<li>MongoDB</li></h5>
<br/>

<p>Authentication Technologies</p>
<h5>
<li>OAuth/OpenID Connect</li>
</h5>
<br/>

<p>Extra Libraries</p>
<h5>
<li>Socket.IO (Socket.IO enables real-time, bidirectional and event-based communication.)</li>
<li>SignalR (SignalR in ASP.NET lets your server-side code push content to connected clients, in real-time, with client SDKs for JavaScript, .NET (C#, F#, and VB))</li>
</h5>
<br/>

# Security
<h5>
Software systems can be attacked to steal information, monitor content, introduce vulnerabilities and damage the behavior of software. Malware can cause DoS (denial of service) or crash the system itself.
</h5>

<p>List of attacks to prevent in the software.</p>
<h5>
<li>Buffer Overflow</li>
<li>Stack Overflow</li>
<li>Command Injection</li>
<li>SQL Injections</li>
</h5>
<br/>

<p>Measures to be taken to secure software during development and on deployment</p>
<h5>
<li>Take regular backup of data to have copies in case of corruption to the original</li>
<li>Install firewalls on the network.</li>
<li>Use encryption software to secure sensitive information</li>
<li>Keep an eye on suspicious activity.</li>
<li>Use multi-factor authentication to verify access requests</li>
</h5>

<h5>The only way to avoid such attacks is to practice good programming techniques. System-level security can be provided using better firewalls. Using intrusion detection and prevention can also aid in stopping attackers from easy access to the system.</h5>
<br />

<p><u>System Flow Diagram</u></p>

[![Alt-Text](/Flowchart.png)]
<br />

# Testing

<h5>1. Setup test environment with minimum hardware requirements that will be used to test the Application.</h5>
<h5>2. Prepare the data needed for the testing. Provide sample that will cause failure if possible to determine the right cause of action on how to handle errors</h5>
<h5>3. Use technologies like lighthouse to test the perfomance, best practices and detect unused files to help boost the speed and usability of the software.</h5>
<br/>

# Deployment

[![Alt-Text](/deployment_planning.png)]

<h5>1. Test the build on multiple environment to see how it responds.</h5>
<h5>2. Reduce the frequency of changes on the releases. Also make sure we have a rollback plan to fall back to when the software breaks on update.</h5>
<h5>3. Automate the process as much as possible. It reduces the likelihood on running into errors. We will use continuous deployment.</h5>
<h5>4. Set metrics to monitor software performance.  We will create custom KPIs that know the performance of the software before and after deployment.</h5>
<br/>

# Handover Process

<p>It’s crucial to have detailed documentation for a successful knowledge transfer plan in software development</p>

<h5>
<li>All the documents shall be written by a developer who takes part in the project and has access to the source codes.</li>
<li>In case developers are not good at writing, ask them to record screencasts to show the main stages of the process: environment setup, environment deployment, and similar.</li>
<li>Project description and features documentation, project structure: this documentation is needed to make your new team understand what the project is about, its features and structure. It will help them to determine what skills they need and within what timeframe they can complete it.</li>
<li>Deploying to the staging and production servers is a must stage that you should include. Making changes in live apps is a very laborious process. That’s why everything should be defined in all details.</li>
<li>CI/CD pipelines will help you to automate the software delivery process and avoid manual errors</li>
</h5>








