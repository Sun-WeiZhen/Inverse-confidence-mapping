# Inverse-confidence-mapping
The contact force between ultrasonic probe and patient directly affects the quality of ultrasonic image. When the contact force is small, the image quality is poor. The purpose of this project is to establish the mapping relationship between image quality and contact force.

The image in the file "IM_0018" is the image sequence generated when the ultrasound doctor collects ultrasound images according to different contact forces

In our project, we try to establish the mapping relationship between ultrasonic image pixels and ultrasonic attenuation characteristics: I=I0 * exp (- 2 * a * x)

Where, I0 is the pixel of the original ultrasonic image, I is the image pixel reduced according to the ultrasonic attenuation characteristics, exp is the index, and a is the ultrasonic attenuation coefficient, which is related to the contact force. Generally, we think that the greater the contact force, the smaller the a. X is the distance between the pixel and the ultrasonic wave source.


IM_0018中的图像是超声科医生根据不同接触力采集超声图像时生成的图像序列

在我们的项目中，我们试图建立超声图像像素与超声波衰减特性之间的关系：I=I0*exp(-2*a*x)
其中，I0是原始超声图像的像素，I是根据超声波的衰减特性降低之后的图像像素，exp表示指数，a是超声波的衰减系数，它与接触力有关，一般我们认为接触力越大，a越小。x是像素与超声波源之间的距离。
