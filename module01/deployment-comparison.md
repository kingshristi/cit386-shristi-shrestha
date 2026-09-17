# Deployment Comparison
# Business Scenario

The business is a small local bakery that sells cakes, bread, pastries and other baked goods to customers in the community.
The bakery has six employees who handle baking, customer services, orders and daily operations.
The bakery has a technology budget of $200 per month. It needs a reliable website where customers can view
products, learn about bakery and place orders online.
Workload Requirements
The workload for the bakery is a customer-facing website. The website must be reachable from outside the bakery so
customers can accessit from home or on their phones. It should be remain available overnight and be able to handle growth as the bakery gains more 
customers and online orders. Employess do not need physical access to the server hardware. The bakery can afford a minimum $200 per month
for workload.

Virtualbox Comparison
What works: Virtualbox can run a virtual machine on a laptop, and the bakery could use it to host a website for testing or a small demonstration.
It is inexpensive if bakery already owns the laptop.
What breaks: A laptop is not designed to be reliable 24/7 public web server.It may be turned off, disconnected or have limited resources.
Making the website reachable from outside the bakery would also require network configuration. This option doesnot fit the bakery's need
for reliable external access and continuous availability.  

Hyper-V on a worksation
What works: Hyper-V can run a virtual machine on a workplace and can provide more resources than a typical laptop.
The bakery could host its website on the virtual machine and configure it for outside access.
What breaks: The workstation would need to remain powered on and connected to the internet continuously. It would also require someone 
to maintain the physical computer. Since the bakery does not want to require physical access to the hardware ,this option does not
fully meet the workload requirements.

Proxmox Host
What works: Proxmox can run a virtual machine and provide a dedicated environment for the bakery's website.It can support more 
resources and growth than a basic laptop or workstation, and the website can be configured for outside access.
What breaks: The bakery need to purchase and maintain a physical proxmox host. Someone would also need to handle hardware maintainance and failures.
Because the bakery does not want anyone to need physical access to the hardware, this option doesnot fully meet the requirements.

Physical PC Comparison
What works: Physical PC could host the bakery website directly without using virtualization. The bakery would have full control over the
hardware and could configure the computer specifically for the website.
What breaks: The PC would need to remain powered on and connected to the internet 24/7. It would also require physical maintenance and hardware repair.This conflicts with the requirement.

Azure Comparison
What works: Azure can host the bakery website in the cloud, making it reachable from outside the bakery. The service can remain available overnight
and can be scaled as the number of customers grows. The bakery would not need physical access to the server hardware.
What breaks: The main concern is cost. The bakery has a maximum technology budget of $200 per month,so the Azure service would need to be selected 
and configured carefully to stay within the budget.

