# Artificial-Vision
The eye is perhaps the most important sensory organ in the human body, not just
because it can capture the view of our environment but because of the visual
cortex which interpret what the eyes captures.  
They collectively enable pattern recognition with
stunning accuracy and unprecedented efficiency. 
The eyes act as a camera and the visual cortex acts as the intelligence unit.
Computer vision is a field of study devoted to teaching computers how to
recognize patterns and understand what these patterns represent. My project was designed to Capturing
videos and performing pattern recognition, using the intelligence layer that interpret what the camera captures. Hence, the focus of
this book is not to teach the reader to create better cameras but to improve the
intelligence layer in providing visual awareness to the blind.
So this project is designed to work in real time, helping users connect with the lens which is able to look remotely through the video camera to 
describe a scene, 
detect people, 
detect object, 
detect directions, 
read a sign, 
and posture recognition.


                                            THE OBJECTIVES AND GOALS OF ARTIFICIAL VISION PROJECT
These are the main goals of the project:
The custom model was trained to better detect people, specific objects and relating information in human like language to the user (Blinds/ People with Visual impairment), though in later works i will be working on implementing posture recognition, describing a scene, detect dirctions etc.

                                                  APPROACH
Object detection models : 
The two most popular models to be used in real-time are the SSD and the YOLO models.But i made use of SSD MODEL

Singe Shot MultiBox Detector (SSD),  This model performs well overall which make it highly suitable to be used in real time object detection. It is a fully Convolutional Neural Network (CNN). Being fully convolutional means that the network can run inference on images with various resolutions. This is very convenient for real life applications.
SSD model have been made to get lower inference time and better accuracy in real time than any other models.

NLP (Relating the information in human Like language) using Offline google translation (pyttsx3)

                                                    METHODS
                                                    
A pretrained SSD model, is trained on the famous COCO(Common Objects in Context) dataset which can recognize up to 80 classes.
This can later be fine-tuned on other different images of specific people and specific object to detects.
The motivation for using this model is that it is state-of-the-art when it comes to speed and accuracin real time.
Not to say it is proven to be the best, but it looks promising and will therefore be use for this project. 
The inspiratioe of using this model comes from the related work done by Gunnarsson



[object_detection.zip](https://github.com/Olubayode/Artificial-Vision/files/6473599/object_detection.zip)


