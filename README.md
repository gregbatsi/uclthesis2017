# Text Generator using GANs

datasets folder contains all the datasets that were used during the experiments

results.zip contains all the results from the experiments, its devided into 3 subfolders : clean_results_in_excel, full_results, sampled_generations & expected_rewards results

How to set up the project:

Download the seqgan_book.zip

As we did not have available a GPU for our experiments we were forced to use CPU, thought it retarded the computations. In order to set up the model the following steps were required:

·         Use Python 2.7

·         Set up the necessary libraries, such as Tensorflow 1.0.1

·         The txt file contains the book we used as our dataset

·         We used 3 different book from Brown corpus

·         Change directory to seqgan_book

·         Finally execute python book_gan.py

In order to install Tensorflow 1.0.1 for Python 2.7 we had to perform the following steps:

curl -s https://storage.googleapis.com/tensorflow |xmllint --format - |grep whl
export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.0.1-py2-none-any.whl
sudo pip install --upgrade $TF_BINARY_URL

