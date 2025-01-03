## Task
Deploy a website about things that you built and deployed on Netlify. The deployment must be auto deploy from your project’s main branch using GitHub Action. Your portfolio website can be accessed by custom domain (example domain : http://budoacademy.rf.gd/ ) and documented on a readme with screenshots. Readme must explain about:

 - Netlify Sign up process & connect Netlify to your Github project
 - Auto Deployment on Github with Netlify
 - How to connect your custom domain and DNS

## Step by step to deploy website using custom domain :

1. Deploy on Netlify  
    a. First, go to netlify.com  
        <p align="center">
          <img src="./deploy/login netlify.png" height="100">
        </p>  
    b. Second, log in using GitHub Acc
        <p align="center">  
          <img src=".\deploy\login netlify.png" height="100">
        </p>  
    c. Third, click on the "Add New Site" button and select "Import an existing project"  
        <p align="center">  
          <img src="./deploy/import site.png" height="100">
        </p>  
    d. Then, choose connect from GitHub  
        <p align="center">  
          <img src="./deploy/connect github.png" height="100">
        </p>
    f. After that, the repository  
        <p align="center">  
          <img src="./deploy/select rep.png" height="100">
        </p>  
    g. Then, fill all the information needed and click the Deploy button
        <p align="center">  
          <img src="./deploy/deploy.png" height="100">
        </p>  
    h. After that, wait for netlify to build your site (it could take a couple minute to an hour).

    i. Then, tada! Your site already deployed.
        <p align="center">  
          <img src="./deploy/deployed site.png" height="100">
        </p> 

2. get custom domain :

    a. First, go niagahoster.co.id
        <p align="center">
          <img src="./deploy/login niagahoster.png" height="100">
        </p> 
    b. Second, log in to niagahoster
        <p align="center">  
          <img src="./deploy/login niagahoster.png" height="100">
        </p> 
    c. Third, go to "Domains" tab and click "Get a New Domain"
        <p align="center">  
          <img src="./deploy/new domain.png" height="100">
        </p> 
    d. After that, type your custom domain name and scroll down to check its availibility.  
        <p align="center">  
          <img src="./deploy/select domain.png" height="100">
        </p> 
    e. Then, select the payment method 
        <p align="center">  
          <img src="./deploy/select payment method.png" height="100">
        </p> 
    f. After that, make the payment
        <p align="center">
          <img src="./deploy/payment.png" height="100">
        </p> 
    f. Finally, you already purchased a custom domain
        <p align="center">  
          <img src="./deploy/domain done.png" height="100">
        </p> 

3. implementing custom domain to your site on Netlify  

    a. First, go back to niagahoster and then find your custom domain then click Manage
        <p align="center">  
          <img src="./deploy/manage domain.png" height="100">
        </p>  
    b. Then, click on the "DNS / Nameservers" tab section and look for the "Nameservers"
        <p align="center">
          <img src="./deploy/dns nameserver.png" height="100">
        </p> 
    c. After that, go back to netlify and choose your deployed site
        <p align="center">  
          <img src="./deploy/deployed site.png" height="100">
        </p> 
    d. Then, on the site overview, look for "Set up your site" section, and click on the "Set up a custom domain"
  
      #### PS: I already did these "naming custom domain" steps and forgot to take a screenshot so, i will guide you further without using pictures

    e. After that, fill the input text with the custom domain you already bought and click verify. If its available, then you can click on "Add domain"
        
    f. Then, go to "Domains" tab section and look for "Name servers" section. Copy all 4 of the Name Servers
        <p align="center">  
          <img src="./deploy/netlify nameserver.png" height="100">
        </p> 
    g. Last, on niagahoster select "DNS/Nameserver" bar, then click on the "Change Nameservers" and paste the Name Servers from the netlify. Then click save 
        <p align="center">  
          <img src="./deploy/dns nameserver.png" height="100">
        </p>
        <p align="center">  
          <img src="./deploy/change nameserver.png" height="100">
        </p>  
        <p align="center">  
          <img src="./deploy/fill nameserver.png" height="100">
        </p> 
    h. Finally, your website already deployed and has it custom domain. You can check your site status on netlify.com (have to wait a moment before the site go online).
        <p align="center">  
          <img src="./deploy/add custom domain.png" height="100">
        </p> 
    i. After the site is online. Now you can use your custom domain to visit your website.