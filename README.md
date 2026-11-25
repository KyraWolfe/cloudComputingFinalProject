# cloudComputingFinalProject
- group members: Naina and Kyra
- Naina: Networking and Security, Database and Backend Integration
- Kyra: Compute and Frontend, Monitoring Logging and Cost Optimization
- to keep all parts of the project together, all work was done on Naina's learner's lab. We met up in person to discuss the separation of work and for Kyra to do her parts on Naina's device since all the parts are connected to the first section, which was done by Naina. Any extra steps needed after the meetups, Naina handled. To balance the workload a bit more, Kyra set up more of the foundations on the reports and did most of the slideshow, leaving Naina to fill in her steps or add any additional information that Kyra missed.
- keeping the entire project on one learner's lab also gave a better idea of how much a project like this would cost
  
# Networking and Security

# Compute and Frontend
- created an S3 bucket with the name (insert name here)
- Naina generated a website using (insert random ai thing here)
- this was added to the S3 bucket for the static web page

- an EC2 was added with the name (insert name here)
- The vockey key pair group was added to the EC2
- A VPC was added that was created during the first section
- the first of the public subnets created was used
- Web Security group was chosen as well
- Auto recovery was enabled in the hopes that all the progress we made with the EC2 would save when we disabled it to save funds, this step may have gone wrong as charges were still happening (may need to update this section or add to it if discovered why it wasnt working right)
- We reused the user script from the Lab 3: Intro to EC2 for this EC2 as well
  
# Database and Backend Integration

# Monitoring, Logging, and Cost Optimazation
- worked on creating an alarm through Cloudwatch that would go off once the CPU Utilization reached over 80%
- had some struggles creating this alarm as the EC2 and parts of the first section were slightly configured incorrectly
- A dashboard of the EC2 running was pulled up to monitor usage

- The billing dashboard was viewed often to take note of costs whilst working on this project
- after combining all parts as best as possible during our first meeting, the cost was about %0.70
- the next day was when we discovered that the EC2 was still operating after being disabled and this brought charges up to about $1.10

# Slideshow info
- add notes on what needs to be added to the slides
- this includes pics, or information

# need to add:
- naina section notes
- pictures for all
- descriptions of each section

- https://canva.link/lltmoz39evlu3sv 
