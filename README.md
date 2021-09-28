# Preventing XSS and CSRF Attacks through JS Sandboxing

![XSS](https://www.askbuddie.com/wp-content/uploads/2019/06/xss.png)

<a href="https://www.veracode.com/security/javascript-security#:~:text=One%20of%20the%20most%20common,return%20malicious%20scripts%20to%20visitors.&text=Another%20common%20JavaScript%20security%20vulnerability,Site%20Request%20Forgery%20(CSRF).">Here is a link to an article on cross site scripting</a>

<p>
    As someone interested in web security, I find it very interesting that Javascript developers could potentially prevent multiple kinds of attacks (CSRF and XSS) by utilizing sandboxing (runing scripts seperatly so they dont have access to each other's information) and utilizing same origin policy (this is a protocol that prevents one site from accessing script data on another site) by writing their browsers to take these into account, but simply do not. <br/> 
    These attacks make it easy for malicious users to steal data and spread malware across servers very easily when these vulnerabilities are identified. That being said, it is heartneing to see that there is a whole subgenre of software dedicated to strictly analyzing Javascript code to idenitfy these vulnerabilities and I would hope to have the opportunity to use one at some point this semester if possible.
</p>

## Student Comments

### H. Atacan Demir

<p>
    I find the concepts Christian brought up really useful for anyone developing code for the web, and would also like to draw attention to the fact that most people have this incorrect conception that react -or any other library/framework for that matter- is xss proof. That is simply not the case. Here is a stackoverflow <a href="https://stackoverflow.com/questions/33644499/what-does-it-mean-when-they-say-react-is-xss-protected">entry</a> on how XSS can be achieven on react. I personally think that blacklisting should not be the first strategy to utilize for any of these sorts of attack vectors, but that people shoud focus on white-listing.
</p>