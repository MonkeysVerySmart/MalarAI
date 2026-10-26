Overview:
This project focuses on developing an Artificial Intelligence (AI) solution to address the escalating malaria cases and high death rates.. The AI tool employs machine learning algorithms and comprehensive datasets to enhance early detection, aiming to reduce mortality rates and improve healthcare outcomes in regions with limited resources, that is accessible to everyone at no cost.

**INSTRUCTIONS WHILE RUNNING**
*Disclaimer: We highly reccomend dividing the code into cells and running it in google colab since it is best done there*

**GENERAL INSTRUCTIONS**
Make sure to adjust all the variable with paths based on your file structure.
Make sure to pip install all modules if not installed already.

**FLASK INSTRUCTIONS**
Make sure to make a static folder.
If havent already, please adjust the template dir and static dir paths
If running on google colab, Run this code before running the flask app, then click on the url it printed to view the flask app


from google.colab.output import eval_js
print(eval_js("google.colab.kernel.proxyPort(5000)"))

**ML INSTRUCTIONS**
HIGHLY Reccomend using a GPU for training (especially colab's NVIDIA ones)
Adjust the filepath for the model that you save and load.


If any problems occur while running, mail us!
Use this google colab link to view and run the code:
https://colab.research.google.com/drive/1ISm-1GnP9tdfLQq1ohr4xZtNcSlDgfEf#scrollTo=A9Nqbh4nlKKF


**POST HACKATHON NOTES**
This project was for TISB Hacks 2024, in collabaration with 3 other team members, including @aadhritp.
We ended up winning the 3rd place prize of 5000 Rs.
The training may be very intensive without a GPU, so I've included a raw .keras file for you to load the weights and run inference immediately.
Flask apps & google colab have changed, now requiring the use of `run_with_ngrok()` + other changes.
Google colab link was also fixed a bit to adhere with newer TensorFlow syntax.


