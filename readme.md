# A5 Spark homework
# plan A
install on laptop

https://www.sicara.ai/blog/2017-05-02-get-started-pyspark-jupyter-notebook-3-minutes
# plan B
install a virtual machine that already has spark and pyspark, like

https://github.com/kadnan/vagrant-spark2

https://app.vagrantup.com/fscm/boxes/spark-jupyter

# plan C
Do not install on laptop but run on google colab.
## resources

required installations on colab:

https://towardsdatascience.com/pyspark-in-google-colab-6821c2faf41c

https://youtu.be/O_fCQ_4kE-0

This should include the Java downgrading

https://stackoverflow.com/questions/58106622/how-to-change-the-java-version-in-google-colab

## This should work by copy and paste
It is hosted on colab as an example of how to get things done. We don't need the recomender system - we only need the setup.

https://colab.research.google.com/github/SJD1882/Big-Data-Recommender-Systems/blob/master/notebooks/MovieLens27M-ALS-Recommender-System.ipynb

# example code for the shakespear homework:

https://vijayn.com/2015/12/13/sparks-reduce-and-reducebykey-functions/#.Xjq9XS2ZPfY

download the textfile to your local machine: in ubuntu / Linux
* install curl: (sudo) apt install curl
* curl -o works-shkspr.txt https://ocw.mit.edu/ans7870/6/6.006/s08/lecturenotes/files/t8.shakespeare.txt
the file starts with many lines of the Gutenberg projects' comments directed at the human reader. These lines do not contain the works of shakespeare. So we should remove them (though given the size of comments compared to the works the comments are neglectible). Use UNIX comands to check the first lines of the file ( head -20 FILENAME ) and remove them ( sed -i 1,20d FILENAME ) 
