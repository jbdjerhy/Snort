# Project Title: Setting Up Snort IDS on Ubuntu

## Project Description:
The project aims to set up and configure Snort, an intrusion detection system, on an Ubuntu instance to monitor network traffic for security threats.

## Project Scope:
This project covers the installation and initial configuration of Snort on an Ubuntu instance.

## Objectives:
1. Install Snort on an Ubuntu instance.
2. Explore and review the snort.conf configuration file.
3. Create a custom test configuration file (test.snort.conf).
4. Validate the custom configuration file using Snort's built-in testing (-T) feature.
5. Create a sample local rule to generate alerts for ICMP (ping) attempts.
6. Disable all preconfigured rules except the local.rules file.
7. Explore configuring rules with Snorpy, a Snort rule management tool.

## Resources:
- Ubuntu instance
- Snort (version 2.9.15.1)
- Snort configuration files (/etc/snort/)
- Custom test configuration file (test.snort.conf)
- Snorpy for rule management (optional)

## Timeline:
1. Set up the Ubuntu instance and install Snort.
2. Review the snort.conf file and create the custom configuration file.
3. Validate the custom configuration using Snort's built-in testing.
4. Create and test a sample local rule for ICMP.
5. Disable preconfigured rules except for local.rules.
6. Explore Snorpy for rule management (optional).

---

- Created a new Ubuntu instance
- Installed Snort using "sudo apt-get install snort -y"
  ![Untitled picture](https://github.com/jbdjerhy/Snort/assets/142699688/4a6f019c-1476-46af-8959-781e4e176d2f)

- Successfully installed Snort version 2.9.15.1
  ![Untitled picture2](https://github.com/jbdjerhy/Snort/assets/142699688/e183237c-b73e-42d4-88b9-4df593c176ba)
  
- Explored the snort.conf file from /etc/snort/
  ![Untitled picture3](https://github.com/jbdjerhy/Snort/assets/142699688/3857eeb3-7f8e-42c5-9720-18fb2232df5b)
  
- Created a test configuration file "test.snort.conf" and validated it with: "sudo snort -T -I inet -c /etc/snort/test.snort.conf"
  ![Untitled picture4](https://github.com/jbdjerhy/Snort/assets/142699688/be2aa19d-3080-4abb-bf33-b101cbcd0328)
  ![Untitled picture5](https://github.com/jbdjerhy/Snort/assets/142699688/705d07e2-285e-4387-86b9-1cb31e66981a)
  
- Created a sample local rule that generates an alert when ICMP (ping attempts) are detected
  ![Untitled picture6](https://github.com/jbdjerhy/Snort/assets/142699688/09802319-bcdf-4467-98e9-5aee7148fb83)
  
- Disabled all preconfigured rules except the local.rules
  ![Untitled picture7](https://github.com/jbdjerhy/Snort/assets/142699688/2031c704-af5c-4bc0-8387-641093a730f7)
  
- Also explored configuring rules with Snorpy (optional)
  ![Untitled picture8](https://github.com/jbdjerhy/Snort/assets/142699688/aa6e0de5-9a41-445a-99a5-9f3c35e56eb3)
