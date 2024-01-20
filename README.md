
# DE Zoomcamp 2024
Add a catchy title to your project. Something that people immediately know what you are doing

# Introduction & Goals
- Introduce your project to the reader
- Orient this section on the Table of contents
- Write this like an executive summary
  - With what data are you working
  - What tools are you using
  - What are you doing with these tools
  - Once you are finished add the conclusion here as well

# Contents

- [Environment setup](#Environment-setup)  
  - [Setting up the environment on GCP cloud VM](#setting-up-the-environment-on-gcp-cloud-vm)
- [Used Tools](#used-tools)
  - [Connect](#connect)
  - [Buffer](#buffer)
  - [Processing](#processing)
  - [Storage](#storage)
  - [Visualization](#visualization)
- [Pipelines](#pipelines)
  - [Stream Processing](#stream-processing)
    - [Storing Data Stream](#storing-data-stream)
    - [Processing Data Stream](#processing-data-stream)
  - [Batch Processing](#batch-processing)
  - [Visualizations](#visualizations)
- [Demo](#demo)
- [Conclusion](#conclusion)
- [Follow Me On](#follow-me-on)
- [Appendix](#appendix)


# Environment setup
- For the course you'll need:  
  * Python 3 (e.g. installed with Anaconda)
  * Google Cloud SDK
  * Docker with docker-compose
  * Terraform
  ## Setting up the environment on GCP cloud VM  
    * Generating SSH keys  
      1. Open Git Bash and under users home dir (/c/Users/Admin) do *__mkdir .ssh__*
      2. From the link, https://cloud.google.com/compute/docs/connect/create-ssh-keys, Create an SSH key pair  
        a. Use cmd - ssh-keygen -t rsa -f KEY_FILENAME(use *__gcp__*) -C USERNAME(*your name preferred*) -b 2048  
        b. Enter passphrase (empty for no passphrase): *just hit enter, we dont want any pass phrase*  
        c. do *ls* and it should list two keys, private key- *gcp* and public key - *gcp.pub*
      3. Configure VM with ssh public key  
        a. In GCP console, under Compute Engine, go to Metadata
        b. Under SSH keys tab, add public SSH Key value and hit save. To copy value of *gcp.pub*, use *__cat gcp.pub__* 
    * Create VM  
      1. Under Create an instance  
        a. Change name to de-zoomcamp  
        b. Select Region  
        c. Under Machine Config, select *series* - *E2* , *Machine type* - *e2-standard-4*   
        d. Under Boot Disk, select *Image type* - *Ubuntu 20.04 LTS*, *size* - *30 GB*  
        e. Hit Create   
      


# Used Tools
- Explain which tools do you use and why
- How do they work (don't go too deep into details, but add links)
- Why did you choose them
- How did you set them up

## Connect
## Buffer
## Processing
## Storage
## Visualization

# Pipelines
- Explain the pipelines for processing that you are building
- Go through your development and add your source code

## Stream Processing
### Storing Data Stream
### Processing Data Stream
## Batch Processing
## Visualizations

# Demo
- You could add a demo video here
- Or link to your presentation video of the project

# Conclusion
Write a comprehensive conclusion.
- How did this project turn out
- What major things have you learned
- What were the biggest challenges

# Follow Me On
Add the link to your LinkedIn Profile

# Appendix

[Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
