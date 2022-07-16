## Introduction
A simple page introduces my projects. All of these can be downloaded in my github repositories.
If you have problem or suggestions, please feel free to contact me.<br>
Email-address:<a href="mailto:xyf07140610@gmail.com">xyf07140610@gmail.com</a>

### Self introduction
 - Name: Frozen-Finger (Xu)
 - job: Student
 - Location: Tokyo & Jiangsu Province, China
 - Hobbies: Snooker, films, music, philosophy
 - Research Feilds: Deep Learning, NLP


# Projects

## AutoEncoder
### An AutoEncoder used for pre-training Vision-Transformer(Encoder)
[link for autoencoder](https://github.com/frozen-finger/masked-autoencoder-for-chinese-character)
 - Task: reconstructing Chinese character graph
 - Structure: Vision-Transformer(Encoder), Transformer(Decoder)<br>
 ![autoencoder structure](/autoencoderstructure.png)
 - Pre-train result:<br>
 ![pre-train result](/pre-train.png)

### Change Chinese character in a sentence into its correponding radical
In this project, we present an easy way to change Chinese character into its corresponding radical.<br>
<hr>
 * Firstly, we record all Chinese character and its correponding radical in a file.
 * Secondly, we set all Chinese characters with same radical into an ordered group.
 * Finally, Chinese character will be changed into its radical and correponding index in the group.
 #### Text
 >
