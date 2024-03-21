# Instructions for getting started with github
1. Create an account with your ICR email address: https://github.com/login?add_account=1&return_to=https%3A%2F%2Fgithub.com%2F
2. Give the username to me along with the service name [RSE Group](mailto:schelpdesk@icr.ac.uk)
3. I will send you back a link to a repo that has a very basic outline of a dummy service
4. You can edit and create your service simply using the web interface, clicking on the edit button and changing the text. This is done with markdown which is a like a simplified form of html - [info here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
5. Once you are happy with a first draft of the service proceed below to linking with  zenodo.

Please ask for help at any point! [RSE Group](mailto:schelpdesk@icr.ac.uk)

# Instructions for linking the repos and DOIs for fixed acknowledgement

Feel free to contact the [RSE Group](mailto:schelpdesk@icr.ac.uk) for help with any part of this.
### Create a repo for your service
   
### Link to zenodo
1. Link the github account you use for ICR with zenodo: [Log on to zenodo](https://zenodo.org/login/?next=%2F) and choose to sign in with github
   - Make sure you grant access to the Institute of Cancer Research institution when you grant access via github
   - You can chose to link to your orcid or your github account
   - You will get an email to confirm your account

### Prepare a release
2. Edit the README.md of the repo with your service details.
3. Look at the [RSE Group](https://github.com/ICR-Services/RSE-Group) as a guide or contact the [RSE Group](mailto:schelpdesk@icr.ac.uk) for assistance.
4. Make a release by going to the release pages on the right of github, or from zenodo's [github page](https://zenodo.org/account/settings/github/). When you navigate to the repo page in zenodo take care to only give access to YOUR repo as you make see a list of institution repos

### Find your badge
5. Back on the Zenodo page a badge is automatically created, with a link to a zip of the code, like [![DOI](https://zenodo.org/badge/755024489.svg)](https://zenodo.org/doi/10.5281/zenodo.10638989)
![image](https://github.com/ICR-Services/Instructions/assets/132372271/c1ce5507-3036-4d86-8adc-3f582d3cc2af)

However, be aware that this is a link to the latest release, so this will change with every release. It may be more appropriate to use the explicit most recent version DOI link so that if anyone uses it it refers to the exact version of the services at that time. To do this, find the release specific DOI button and click it:
![image](https://github.com/ICR-Services/Instructions/assets/132372271/769534f8-2cb4-4f94-8815-f3074cd19d15)

Take a copy of the DOI link from this badge for the pinned version (choose link, markdowen etc, I am using markdown in this example)
![image](https://github.com/ICR-Services/Instructions/assets/132372271/6448d3e2-a8ae-40cf-9ce5-86a3471fd5b0)


Finally, the dynamic DOI for this service is this:
[![DOI](https://zenodo.org/badge/755024489.svg)](https://zenodo.org/doi/10.5281/zenodo.10638989)  
```[![DOI](https://zenodo.org/badge/755024489.svg)](https://zenodo.org/doi/10.5281/zenodo.10638989)```

But at the time of writing the latest is v1.0.5: 
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10684363.svg)](https://doi.org/10.5281/zenodo.10684363)  
```[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10684363.svg)](https://doi.org/10.5281/zenodo.10684363)```

The number will be the same while v1.0.5 is the most recent release.




