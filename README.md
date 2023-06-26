# Time-and-Energy-Efficient-task-offloading-and-Scheduling-Algorithm-in-a-3-tier-Fog-Architecture

As the complexity of the applications we use on mobile devices increases, a constraint arises due
to this, which is the computational capacity of these devices. We have resource intensive
applications like augmented reality which have real time constraints or near real time constraints.
Mobile devices are hence unable to execute media rich tasks and tasks like data analysis
involving a high computational threshold.
One way to navigate through this issue of Mobile devices in comparison to their non-mobile
counterparts is the use of Cloud Computing. Cloud computing technology is provided by Cloud
Service Providers like Amazon, Rackspace and many more. They provide the operational
backbone to execute these tasks on behalf of the mobile devices. The cloud provides the
necessary resources and infrastructure for the tasks to be executed. The concept of handing off
resource intensive tasks from a mobile device to resource rich infrastructure is called Offloading.
Thus it may seem like the concept of Cloud and the process of offloading tasks can alleviate the
problem discussed above. This may indeed be a viable solution but we have to factor in key
components like time and distance into this equation. Offloading a task involves handing off data
to the cloud and receiving the processed data back from the cloud. The key issue however here is
that Cloud Resources are located far away from these mobile devices and hence there is
excessive latency.
Thus we go for an architecture where there is a layer between the mobile IoT devices and our
Cloud layer in order to reduce this latency and offload the tasks to this layer. This is called the
Fog layer or sometimes referred to as Edge devices. The compute process which takes place at
this layer can be termed as MEC or Mobile Edge Computing. The simplest fog architecture is the
3 layer architecture
