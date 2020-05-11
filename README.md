# ROS package: hamdan_topics 
The first package, that has a publisher and subscriber, has been done for both topic, message and doubler. I have descaver while loop for topic_publisher while the publisher count the topic counter via the method of the oblect publigh. this is useful because it gives the avrage rate te topic that it's been publish to. Also, rate has sleep method to keep the loob into its loop at chosen rate. In addition, topic_ subscriber callback function with every new message. messages of complex print in the trminal the imgaginary numbers and real numbers. doubler node used to double in the numbers coming in to the subscriber.  

## Requirements
This type of system will run on ROS melodic on Unbuntu 18.04 version.

## Installation and configuration
Here I am going to list the processes on how hamdan_topics has been installed. First, to create a new packege I have used <catkin_create_pkg hamdan_topics \rospy std_msgs message_runtime message_generation>. Second I've touched hamdan_topics using <touch hamdan_topics/src/topic_publisher.py>. After that I created the new packege I have to make it executable by using chmod u+x hamdan_topics/src/topics_publisher.py. Also, I added all the dependecies to the package to the fllowing:
topic_publisher.py, topic_subscriber.py, message_publisher.py,  message_subscriber.py and doubler.py. 
Then, I wrote the codes and using catkin_make to make it the package available. I source it using source devel/setup.bash. After all that, we run it by using rosrun my_topics topic_publisher.py. When I finished from the package creation I clone it to git hub by doing the following: 
git -A
git status
then git commit -m
git status
git push
this will send my work to github raspratory Final.

## Getting started 
To get the package work, I went back to the rate < hamdan/hamdan/01>. I start 'roscore' service we can run our node rosrun hamdan_topics topic_publisher.py. Then, opening new trminal and start hamdan_topics topic_subscriber.py. 

## Usage
usage of my package is to count of who's publishing and subscribing to the counter.

# ROS package: hamdan_services 
How can you count the words that you write in google dous or microsfot word? This package opration (hamdan_sevices) is to count how many works are written in the program. 

## Requirements
This type of system will work in ROS version.

## Installation and configuration
There is there process on how I install hamdan_services. First, to create a packege I used ( catkin_create_pkg hamdan_services \rospy std_msgs message_runtime message_generation). second I touch it by using (touch hamdan_services/src/topic_publisher.py).After creating the new packege I have to make it executable by using chmod u+x hamdan_services/src/topics_publisher.py. Then, I wrote the codes and using catkin_make to make it the package available. Then, I source it using source devel/setup.bash. After all that, we run it by using rosrun my_services topic_publisher.py.

## Getting started
the package could be used in counting the words that been writing in the program. 

## Usage
usage of my package is to count of who's publishing and subscribing.

# ROS package: hamdan_actions
allow to make request for action and receive a respone for a result 

## Requirements
This type of system will work in ROS version.

## Installation and configuration
There is there process on how I install hamdan_actions. First, to create a packege I used ( catkin_create_pkg hamdan_actions \rospy std_msgs message_runtime message_generation). second I touch it by using (touch hamdan_actions/src/topic_publisher.py).After creating the new packege I have to make it executable by using chmod u+x hamdan_actions/src/topics_publisher.py. Then, I wrote the codes and using catkin_make to make it the package available. Then, I source it using source devel/setup.bash. After all that, we run it by using rosrun my_actions topic_publisher.py.

## Getting started
I use hamdan_cation to do long calucation. 

## Usage
I use hamdan_cation to do long calucation. 

## Here's a subsction 

[Here's my YouTube channel link](https://www.youtube.com/channel/UCDvrSfLtLuQEP77V12sMbag)


## Here's where I am going to start my final 
