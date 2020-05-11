# ROS package: hamdan_topics 
The first package, that has a publisher and subscriber, has been done for both topic, message and doubler. I have discovered a while loop for topic_publisher while the publisher count the topic counter via the method of the object publigh. This is useful because it gives the average rate of the topic that it's been published to. Also, rate has a sleep method to keep the loop into its loop at chosen rate. In addition, topic_ subscriber callback function with every new message. messages of complex print in the terminal the imaginary numbers and real numbers. doubler node used to double in the numbers coming in to the subscriber.  

## Requirements
This type of system will run on ROS melodic on Ubuntu 18.04 version.

## Installation and configuration
Here I am going to list the processes on how hamdan_topics has been installed. First, to create a new package I have used <catkin_create_pkg hamdan_topics \rospy std_msgs message_runtime message_generation>. Second I've touched hamdan_topics using <touch hamdan_topics/src/topic_publisher.py>. After that I created the new package I have to make it executable by using chmod u+x hamdan_topics/src/topics_publisher.py. Also, I added all the dependencies to the package to the following:
topic_publisher.py, topic_subscriber.py, message_publisher.py,  message_subscriber.py and doubler.py. 
Then, I wrote the codes and used catkin_make to make it available. I source it using source devel/setup.bash. After all that, we run it by using rosrun my_topics topic_publisher.py. When I finished from the package creation I clone it to github by doing the following: 
git -A
git status
then git commit -m
git status
git push
this will send my work to github raspratory Final.

## Getting started 
To get the package work, I went back to the rate < hamdan/hamdan/01>. I start a 'roscore' service where I can run our node rosrun hamdan_topics topic_publisher.py. Then, open a new terminal and start hamdan_topics topic_subscriber.py.

## Usage
The usage of my package is to count who's publishing and subscribing to the counter.

# ROS package: hamdan_services 
How can any system count the words that someone writes using google docs or microsoft word? Hamdan_services is a ROS package that contains two dependencies. One of them is service_server which imports and makes wait for the service. Also, it set up the proxy server communication. Send one is service_client which prints out what is happening in therosnode. This is useful because it could be used to count how many works are written in the program.

## Requirements
This type of system will run on ROS melodic on Ubuntu 18.04 version.

## Installation and configuration
Here I am going to list the processes on how hamdan_services has been installed. First, to create a new package I have used <catkin_create_pkg hamdan_services \rospy std_msgs message_runtime message_generation>. Second I've touched hamdan_services using <touch hamdan_services/src/topic_publisher.py>. After that I created the new package I have to make it executable by using chmod u+x hamdan_services/src/topics_publisher.py. Also, I added all the dependencies to the package to the following: Topic_publisher.py and topic_subscriber.py
Then, I wrote the codes and used catkin_make to make it available. I source it using source devel/setup.bash. After all that, we run it by using rosrun my_topics topic_publisher.py. When I finished from the package creation I clone it to github by doing the following: 
git -A
git status
then git commit -m
git status
git push
this will send my work to  github raspratory Final.

## Getting started
To get the package work, I went back to the rate < hamdan/hamdan/01>. I start a 'roscore' service where I can run our node rosrun hamdan_services topic_publisher.py. Then, open a new terminal and start rosrun hamdan_topics topic_subscriber.py.

## Usage
the package could be used in counting the words that been writing in the program. 

# ROS package: hamdan_actions
The third package, that has the main communication mechanism in ROS. This package has a publisher and subscriber that has been done for hamdan_actions. It allows the user to make requests for action and receive a response for a result. It contains two dependencies: fancy_action_server and fancy_action_client. It is useful because it can  navigate to a location, performing a complex manipulation, or performing a long calculation. 

## Requirements
This type of system will run on ROS melodic on Ubuntu 18.04 version.

## Installation and configuration
There is there process on how I install hamdan_actions. First, to create a packege I used ( catkin_create_pkg hamdan_actions \rospy std_msgs message_runtime message_generation). second I touch it by using (touch hamdan_actions/src/topic_publisher.py).After creating the new packege I have to make it executable by using chmod u+x hamdan_actions/src/topics_publisher.py. Then, I wrote the codes and using catkin_make to make it the package available. Then, I source it using source devel/setup.bash. After all that, we run it by using rosrun my_actions topic_publisher.py. When I finished from the package creation I clone it to github by doing the following: 
git -A
git status
then git commit -m
git status
git push
this will send my work to  github raspratory Final.

## Getting started
This is started with roslaunch.

## Usage
The usage of this roslaunch is to test if everthing works right such as a long calucation.

## Here's a subsction 

[Here's my YouTube channel link](https://www.youtube.com/channel/UCDvrSfLtLuQEP77V12sMbag)


## Here's where I am going to start my final 
