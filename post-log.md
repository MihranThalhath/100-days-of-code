# Post #100DaysOfCode Log - Dashiell Bark-Huss

I completed my 365 days of code. But I'm going to continue to add to this log when I want to save notes.

<h3 id="deeplearning-2"></h3>

### Deep Learning
6/6/20 - 6/8/20

[3Brown1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw) deep learning series -  [Neural networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi). Superb visuals. He had great content for when I was learning about (brainwave) signal processing as well.

#### [Neural networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) by [3Brown1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw):

1. [But what is a Neural Network? | Deep learning, chapter 1](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=1)

2. [Gradient descent, how neural networks learn | Deep learning, chapter 2](https://www.youtube.com/watch?v=IHZwWFHWa-w&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=2)

3. [What is backpropagation really doing? | Deep learning, chapter 3](https://www.youtube.com/watch?v=Ilg3gGewQ5U&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=3)

4. [Backpropagation calculus | Deep learning, chapter 4](https://www.youtube.com/watch?v=tIeHLnjs5U8&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=4)

Video: [A Friendly Introduction to Generative Adversarial Networks (GANs)](https://www.youtube.com/watch?v=8L11aMN5KY8)
*Tutorial with python follow along on GANs, the machine learning framework used in deepfakes.*


[Repo for tutorial above](https://github.com/luisguiserrano/gans)


Article: [GANs from Scratch 1: A deep introduction. With code in PyTorch and TensorFlow](https://medium.com/ai-society/gans-from-scratch-1-a-deep-introduction-with-code-in-pytorch-and-tensorflow-cb03cdcdba0f)

ML vs AI
>For those new to the field of Artificial Intelligence (AI), we can briefly describe Machine Learning (ML) as the sub-field of AI that uses data to “teach” a machine/program how to perform a new task. [*source*](https://medium.com/ai-society/gans-from-scratch-1-a-deep-introduction-with-code-in-pytorch-and-tensorflow-cb03cdcdba0f)

[How Machines Learn](https://www.youtube.com/watch?v=R9OHn5ZF4Uo)

[The Rise of the Machines – Why Automation is Different this Time](https://www.youtube.com/watch?v=WSKi8HfcxEk)

[Lecture 13 | Generative Models](https://www.youtube.com/watch?v=5WoItGTWV54) - *only watched a little*


#### Question:
Are there libraries that help machines learn faster by feeding it what another machine already learned? 

*For example,* let's say I have a collection of text messages. I wrote half of them and Shlomo, my bff/lover, wrote the other half. I want a machine to learn to detect which texts I wrote and which Shlomo wrote. In this situation, are there libraries of neural networks that have already taught a machine about the english language? Otherwise my machine with have to learn to recognize so much from scratch.

Is a library like this a thing? Or do you always have to train a machine from scratch?

I posted this question on [reddit](https://www.reddit.com/r/learnmachinelearning/comments/gzc1wp/does_machine_learning_always_start_from_scratch/). I wanted to find a slack or discord to post it on. But I haven't found a good slack or discord for beginners learning ML. 

I got an answer
>For NLP, your best best is probably scapy, as it comes with three English models ready to deploy. You will still need labels in your training data for who wrote what note, but tokenization, stemming, word vector generation, etc should be ready to go for preprocessing!
>
>Hint: in other **prebuilt models**, you can also add on to them using **transfer learning**

Prebuilt models & [transfer learning](https://en.wikipedia.org/wiki/Transfer_learning#:~:text=Transfer%20learning%20(TL)%20is%20a,when%20trying%20to%20recognize%20trucks.) is what I'm talking about I guess!

Not related to deep learing: **Tim Ferris/ Noah Kagan Article on business**- [How to Create a Million-Dollar Business This Weekend (Examples: AppSumo, Mint, Chihuahuas)](https://tim.blog/2011/09/24/how-to-create-a-million-dollar-business-this-weekend-examples-appsumo-mint-chihuahuas/)

<h3 id="deeplearning-1"></h3>

### Deep Learning
6/4/20 - 6/6/20

Watching this series- this is the first video- [How to Make a Prediction - Intro to Deep Learning #1](https://www.youtube.com/watch?v=vOppzHpvTiQ&list=PL2-dafEMk2A7YdKv4XfKpfbTH5z6rEEj3) 
  - Machine learning vs Neural Network vs Deep Learning are all different things
  - **Machine Learning:** Traditionally, programming is defining every step for a ccomputer to take to get to an outcome. Machine learning is backwards. You Show the computer the outcome and the computer learns how to get there.
  - **Neural Networks:** There are a lot of mahcine learning models. One of them is called a Neural Network.
  - **Deep Learning:** When we use a Neural Network that's not just one or two but many layers deep to make a prediction.

Machine Learning 3 Styles:
- Supervised
- Unsupervised
- Reinforcement

Regression: a machine learning task.

Pandas let's you read your data set.
sklearn- machine learning librayr
matplot lib- lets you visualize your model and data.

Neural Network- a biologically inspired algorithm that learns to identify patterns in data.

Backpropagation is a technique to train a Neural Net by updating weights via gradient descent.

Deep learning= many layer neural net + big data + big compute

<h3 id="avatarify-2"></h3>

### More Deepfakes & Avatarify 
6/3/20 - 6/4/20

Avatarify keeps [freezing](#avatarify-freezing). It's hard for me to figure out why. Maybe it has something to do with Google Colab? I will try to understand mroe about Colab.

From [Welcome To Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb):
>Colaboratory, or "Colab" for short, allows you to write and execute Python in your browser, with
>
>- Zero configuration required
>- Free access to GPUs
>- Easy sharing
>
>Whether you're a student, a data scientist or an AI researcher, Colab can make your work easier. 

It reminds me of a Jupyter Notebooks. Oh I guess it is a Jupyter Notebook?

>**What is the difference between Jupyter and Colab?**
>
>Jupyter is the open source project on which Colab is based. Colab allows you to use and share Jupyter notebooks with others without having to download, install, or run anything.

*-from [Colaboratory FAQ](https://research.google.com/colaboratory/faq.html)*

From [Welcome To Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb):
>Colab notebooks execute code on Google's cloud servers, meaning you can leverage the power of Google hardware, including GPUs and TPUs, regardless of the power of your machine. All you need is a browser.

Could the problem be with Ngrok? What is Ngrok?

>**What is ngrok?**
>
>ngrok exposes local servers behind NATs and firewalls to the public internet over secure tunnels.

*-from [ngrok](https://ngrok.com/product)*

[Network address translation (NAT)](https://en.wikipedia.org/wiki/Network_address_translation)

Video: [NAT Explained - Network Address Translation](https://www.youtube.com/watch?v=FTUV0t6JaDA)

Video: [What is ngrok?](https://www.youtube.com/watch?v=UaxqJUXqvro)
  - It lets anyone access your local website.

### Ali Replied On Slack
I had posted on the avatarify slack:
>My terminal was showing all this around the time it froze. Seemed to go from sending and receiving data to predict returned None  and  recv_queue is empty
>```bash
>[1591061619.742012] PACK 1.651 (1.518)		UNPACK 0.888 (1.153)		
>[1591061620.019460] SEND 0.111 (0.116)		
>[1591061620.803449] RECV 107.846 (44.370)		
>[1591061620.805253] PACK 1.613 (1.520)		UNPACK 1.687 (1.158)		
>[1591061621.087406] SEND 0.107 (0.116)		
>[1591061621.356967] recv_queue is empty
>[1591061621.357040] predict returned None
>[1591061621.836266] RECV 99.935 (44.233)		
>[1591061621.837547] PACK 1.561 (1.521)		UNPACK 1.189 (1.159)		
>[1591061622.072949] recv_queue is empty
>[1591061622.073058] predict returned None
>[1591061622.088352] SEND 0.133 (0.116)		
>[1591061622.188220] recv_queue is empty
>[1591061622.188299] predict returned None
>[1591061622.301631] recv_queue is empty
>[1591061622.301709] predict returned None
>[1591061622.414096] recv_queue is empty
>[1591061622.414171] predict returned None
>[1591061622.526833] recv_queue is empty
>[1591061622.526892] predict returned None
>[1591061622.638287] recv_queue is empty
>[1591061622.638335] predict returned None
>[1591061622.748865] recv_queue is empty
>```

I just checked the Avatarify Slack and Ali answered:

>Looks like the server stopped, did you check that?

Wait a minute, when did I run a server? I mean I knew I did. But I didn't really think about it. 

>## Technical details
>The client on your computer connects to the server via ngrok TCP tunnel or a reverse ssh tunnel.

*-from the avatarify Colab file*


[What is TCP/IP?](https://www.youtube.com/watch?v=PpsEaqJV_A0)

Well I ran the preview again and I haven't had a problem again with freezing. I think it might just be that the internet over here sucks balls. I've had a lot of lagging but no freezing. My Google Colabs rendered avatar will sometimes lag a whole minute behind my computer preview.

### Client Not Starting Again
I'm getting the problem where the client isn't starting again. Maybe it's the internet at the house I'm at.

I ran `./run_mac.sh --is-client --in-addr tcp://0.tcp.ngrok.io:<some #> --out-addr tcp://0.tcp.ngrok.io:<some #>` in my client.

It got stuck again:
```bash
[1591295183.195187] Loading Predictor
[1591295183.249625] Sending to tcp://0.tcp.ngrok.io:19494
[1591295183.249688] Receiving from tcp://0.tcp.ngrok.io:18279
[1591295183.251305] SEND 0.289 (0.289)	
```

So I opened a new terminal so I could keep the tcp tunnel open and cd'd into my avatarify directory and got the info from the logs:

#### Client Logs

```bash
# cam_fomm.log
$ cat ./var/log/cam_fomm.log | head -100

[1591295183.195119] Loading Predictor

# recv_worker.log
$ cat ./var/log/recv_worker.log | tail -100

[1591295183.249530] Receiving from tcp://0.tcp.ngrok.io:18279

# predictor_remote.log
$ cat ./var/log/predictor_remote.log | tail -100

# send_worker.log
$ cat ./var/log/send_worker.log | tail -100

[1591295183.249461] Sending to tcp://0.tcp.ngrok.io:19494
[1591295183.250705] SEND 0.289 (0.289)		
```

#### Logs from the **server(Google Colab)**

```bash
# cam_fomm.log
!cat ./var/log/cam_fomm.log | head -100

[1591295131.469881] Loading Predictor

# recv_worker.log
!cat ./var/log/recv_worker.log | tail -100

[1591295136.497368] Receiving on port 5557
[1591295137.498841] recv timeout
[1591295138.500048] recv timeout
[1591295139.501354] recv timeout
[1591295140.502621] recv timeout
[1591295141.503973] recv timeout
[1591295142.505343] recv timeout
[1591295143.506708] recv timeout
[1591295144.508054] recv timeout
[1591295145.509405] recv timeout
[1591295146.510674] recv timeout
[1591295147.512001] recv timeout
[1591295148.513307] recv timeout
[1591295149.514569] recv timeout
[1591295150.515866] recv timeout
[1591295151.517149] recv timeout
[1591295152.518417] recv timeout
[1591295153.519695] recv timeout
[1591295154.520933] recv timeout
[1591295155.521329] recv timeout
[1591295156.522362] recv timeout
[1591295157.523621] recv timeout
[1591295158.524339] recv timeout
[1591295159.525671] recv timeout
[1591295160.526322] recv timeout
[1591295161.527560] recv timeout
[1591295162.528859] recv timeout
[1591295163.530099] recv timeout
[1591295164.531374] recv timeout
[1591295165.532618] recv timeout
[1591295166.533880] recv timeout
[1591295167.535235] recv timeout
[1591295168.536511] recv timeout
[1591295169.537745] recv timeout
[1591295170.538969] recv timeout
[1591295171.540282] recv timeout
[1591295172.541613] recv timeout
[1591295173.542851] recv timeout
[1591295174.543134] recv timeout
[1591295175.544391] recv timeout
[1591295176.545623] recv timeout
[1591295177.546854] recv timeout
[1591295178.548073] recv timeout
[1591295179.549387] recv timeout
[1591295180.550594] recv timeout
[1591295181.551827] recv timeout
[1591295182.553060] recv timeout
[1591295183.553402] recv timeout
[1591295184.037698] RECV 483.494 (483.494)		
[1591295185.040406] recv timeout
[1591295186.041745] recv timeout
[1591295187.043012] recv timeout
[1591295188.044255] recv timeout
[1591295189.045485] recv timeout
[1591295190.046714] recv timeout
[1591295191.047975] recv timeout
[1591295192.049220] recv timeout
[1591295193.050551] recv timeout
[1591295194.051841] recv timeout
[1591295194.051943] recv_worker exit

# predictor_worker.log
!cat ./var/log/predictor_worker.log | tail -100

[1591295184.038878] working on {'name': '__init__', 'critical': True, 'id': 0}
[1591295193.297287] predictor_worker error
[1591295193.300892] predictor_worker exit

# send_worker.log
!cat ./var/log/send_worker.log | tail -100

[1591295136.503218] Sending on port 5558
[1591295137.504635] send queue empty
[1591295138.505828] send queue empty
[1591295139.507043] send queue empty
[1591295140.508257] send queue empty
[1591295141.509450] send queue empty
[1591295142.510346] send queue empty
[1591295143.511650] send queue empty
[1591295144.512894] send queue empty
[1591295145.514138] send queue empty
[1591295146.515354] send queue empty
[1591295147.516279] send queue empty
[1591295148.517272] send queue empty
[1591295149.517987] send queue empty
[1591295150.519198] send queue empty
[1591295151.520380] send queue empty
[1591295152.521587] send queue empty
[1591295153.522778] send queue empty
[1591295154.523971] send queue empty
[1591295155.524925] send queue empty
[1591295156.526128] send queue empty
[1591295157.527365] send queue empty
[1591295158.528545] send queue empty
[1591295159.529786] send queue empty
[1591295160.530956] send queue empty
[1591295161.532146] send queue empty
[1591295162.533465] send queue empty
[1591295163.534664] send queue empty
[1591295164.535904] send queue empty
[1591295165.537098] send queue empty
[1591295166.538343] send queue empty
[1591295167.539559] send queue empty
[1591295168.540751] send queue empty
[1591295169.541870] send queue empty
[1591295170.543054] send queue empty
[1591295171.543232] send queue empty
[1591295172.544419] send queue empty
[1591295173.545583] send queue empty
[1591295174.546774] send queue empty
[1591295175.547964] send queue empty
[1591295176.549147] send queue empty
[1591295177.550433] send queue empty
[1591295178.551604] send queue empty
[1591295179.552792] send queue empty
[1591295180.553991] send queue empty
[1591295181.555143] send queue empty
[1591295182.556268] send queue empty
[1591295183.557460] send queue empty
[1591295184.558509] send queue empty
[1591295185.559216] send queue empty
[1591295186.560523] send queue empty
[1591295187.561821] send queue empty
[1591295188.563108] send queue empty
[1591295189.564446] send queue empty
[1591295190.565701] send queue empty
[1591295191.566970] send queue empty
[1591295192.567348] send queue empty
[1591295193.568681] send queue empty
[1591295193.568788] send_worker exit

```

I think Google Colab is interesting, and might help me learn how to help other people use a remote GPU. However, I couldn't skip all of this hassle by getting an Nvidia GPU. I thought you could not use them with Apple products, but I think that's not entirely true if you have some coding skills. I also wonder how close Ali is to creating a non-Nvidia version of this project? How many other projects use only Nvidia?
``` bash

!ps

    PID TTY          TIME CMD
      1 ?        00:00:00 run.sh
      9 ?        00:00:02 node
     24 ?        00:00:03 jupyter-noteboo
    116 ?        00:00:00 tail
    124 ?        00:00:02 python3
    256 ?        00:00:00 bash
    261 ?        00:00:03 ngrok
    337 ?        00:00:00 bash <defunct>
    426 ?        00:00:00 ps
```

<h3 id="avatarify-1"></h3>

### Avatarify 
6/1/20 - 6/2/20

[avatarify](https://github.com/alievk/avatarify) is an open source "deepfake" program that you can use live on Zoom. For example, you can Zoom into your meeting as Einstein so people will take you seriously.

I followed the instructions for installing avatarify on my mac and then I followed the instructions to run the Google Colab.

#### Notes on following the [readme](https://github.com/alievk/avatarify) and Google Colab instructions:

- Make sure you're doing the Colab in your own copy. I'm not sure how the Colab works, but I think it's sort of like Google docs- if you make changes to the document, you changed it for everyone. So before you even start playing with the Colab you should *copy to drive* and run your copy of the Colab.
<img src="log_imgs/avatarify_colab_6-2-20-1.png">

- Remember to restart the terminal after installing miniconda before running `bash scripts/install_mac.sh`. Otherwise you could get an error: `-bash: conda: command not found`.

### Freezing Up
When I run avatarify in Google Colab, sometimes nothing happens when I try to start the client.

I'll run the script in my terminal:

`./run_mac.sh --is-client --in-addr tcp://0.tcp.ngrok.io:<# collab it gives you> --out-addr tcp://0.tcp.ngrok.io:< # collab gives you >`

And I get back  something like this:
```bash
[1590494901.630968] Loading Predictor
[1590494901.735869] Receiving from tcp://0.tcp.ngrok.io:15702
[1590494901.735815] Sending to tcp://0.tcp.ngrok.io:16110
[1590494901.747087] SEND 3.435 (3.435)
```

And nothing happens. A lot of things seem to cause this problem: another process might still be running from last time or you might have accidentally changed some code. To stop this from happening, I start all over. Sort of like refreshing everything.

#### Here's how I refresh everything.

1. **BEFORE YOU START:** First, make sure you're doing everything in your own version of the avatarify Colab. I'm not sure how Colab works, but I think it's sort of like Google docs- if you make changes to the document, you changed it for everyone. So before you even start playing with the Colab you should *copy to drive* and run the Colab on your copy.
<img src="log_imgs/avatarify_colab_6-2-20-1.png"> 

1. When you run into a problem (like I did with the client not starting), revert to the original state: 
   1. <img src="log_imgs/avatarify_colab_6-2-20-2.png">
   2. <img src="log_imgs/avatarify_colab_6-2-20-3.png">
   3. <img src="log_imgs/avatarify_colab_6-2-20-4.png" width="70%">
   4. <img src="log_imgs/avatarify_colab_6-2-20-5.png" width="70%">
   5. <img src="log_imgs/avatarify_colab_6-2-20-6.png" width="70%">
   5. <img src="log_imgs/avatarify_colab_6-2-20-7.png">
   
2. And terminate any running sessions
     1. <img src="log_imgs/avatarify_colab_6-2-20-8.png">
     2. <img src="log_imgs/avatarify_colab_6-2-20-9.png">
     3. <img src="log_imgs/avatarify_colab_6-2-20-10.png">

3. On your computer, start a new terminal just in case.

<h3 id="avatarify-freezing"></h3>

### Preview Freezing 
When I do get the preview to appear after running
`./run_mac.sh --is-client....` it will start working and then freeze. As seen here:

  <img src="log_imgs/einstein_froze_6-2-20.gif">

This is where I am stuck. 

Looking at this, I realize Einstein and I both have ample flyaways. Does this mean I'm a genius too?

#### Next Steps
The next steps are 
   1. Getting the preview to stop freezing. 
   2. Connecting the preview to Zoom.

### Some More Avatars
#### Nat Sharpe
Friend and fellow coder and bad ass [Nat Sharpe](https://www.linkedin.com/in/nat-sharpe/):

  - <img src="log_imgs/nat_avatar_6-2-20.gif">
#### Adam Stillman
[Adam Stillman](https://www.linkedin.com/in/adamjstillman/), Cousin. With my swagger and his punim, we have the potential to be the next American heart throb:

  - <img src="log_imgs/adam_avatar_6-2-20.gif">
#### Einstein
My hairstyle twin!

  - <img src="log_imgs/einstein_avatar_6-2-20.gif">





### Deep Learning
5/29/20 - 6/1/20

#### Messy Notes on Deep Learning

[CUDA Explained - Why Deep Learning uses GPUs](https://www.youtube.com/watch?v=6stDhEA0wFQ)

What I learned from this^ video:
- GPU's are different that CPU's because they have thousands of cores which means they can compute a lot in parallel.

>The main difference between CPU and GPU architecture is that a CPU is designed to handle a wide-range of tasks quickly (as measured by CPU clock speed), but are limited in the concurrency of tasks that can be running. A GPU is designed to quickly render high-resolution images and video concurrently.

*-from [CPU vs GPU | Definition and FAQs | OmniSci](https://www.omnisci.com/technical-glossary/cpu-vs-gpu)*

This makes  GPU's ideal for deep learning because neural networks are embarrassingly parallel. I'm not being dramatic. [Embarrassingly parallel](https://en.wikipedia.org/wiki/Embarrassingly_parallel) is the actual term, and it means what it sounds like:

>Parallel computing, a paradigm in computing which has multiple tasks running simultaneously, might contain what is known as an embarrassingly parallel workload or problem (also called perfectly parallel, delightfully parallel or pleasingly parallel). An embarrassingly parallel task can be considered a trivial case - little or no manipulation is needed to separate the problem into a number of parallel tasks.

Apple Vs. Nvidia
[Why Apple Ditched Nvidia Graphics Cards](https://www.youtube.com/watch?v=hbk782qET5U)

[Nvidia and Apple’s feud continues as macOS chopped from GPU toolkit](https://www.pcgamesn.com/nvidia/apple-cuda-toolkit-support)

Since content creators use Macs(this is my assumption), and Nvidia doesn't work with Mac, what is the future of these hardwares? Who will win?

>It's like Apple launching the original Macintosh without support for DOS software, or iPod without any way to playback Windows Media Player files, an iPhone without Java, or iPad without Adobe Flash. It's boldly insane to pundits, but it's also exactly the kind of high stakes gamble that has regularly worked out well for Apple and its customer base.

*-from [Editorial: Mac Pro puts the pedal to Metal in Apple's race with Nvidia](https://appleinsider.com/articles/19/10/18/editorial-mac-pro-puts-the-pedal-to-metal-in-apples-race-with-nvidia)*

**GPGPU:**

>General-purpose computing on graphics processing units (GPGPU, rarely GPGP) is the use of a graphics processing unit (GPU), which typically handles computation only for computer graphics, to perform computation in applications traditionally handled by the central processing unit (CPU).

*-from [General-purpose computing on graphics processing units](https://en.wikipedia.org/wiki/General-purpose_computing_on_graphics_processing_units)*

> There isn't a clear answer if the issue is Nvidia refusing to support Apple's Metal, or Apple refusing to officially approve Nvidia's drivers. It appears to be both. Apple pretty clearly has a vested interest in expanding industry support for its Metal API, the same as Nvidia with its CUDA platform.

*-from [Editorial: Mac Pro puts the pedal to Metal in Apple's race with Nvidia](https://appleinsider.com/articles/19/10/18/editorial-mac-pro-puts-the-pedal-to-metal-in-apples-race-with-nvidia)*

CUDA vs OpenCl vs Metal?

>Nvidia GPU’s have built in hardware accelerated ray tracing and AND[sic AMD] does not.

*-My dad*

>AMD has detailed the next generation of Radeon graphics processing units codenamed "Navi 2X," with the RDNA 2 family anticipated to **include hardware ray tracing**

*-from [AMD Radeon 'Navi 2X' cards will offer ray tracing to future Macs](https://appleinsider.com/articles/20/03/09/amd-radeon-navi-2x-cards-will-offer-ray-tracing-to-future-macs)*

Although for deep learning and other general-purpose GPU  stuff I don’t know if ray tracing matters. It just a [graphics rendering technique](https://www.youtube.com/watch?v=0FMlPUEAZfs). 

[First Order Motion Model for Image Animation](https://www.youtube.com/watch?v=lE-4w8q_5GU)

[avatarify](https://github.com/alievk/avatarify)
-remember to restart the terminal after installing miniconda before running `bash scripts/install_mac.sh`


### Making A Demo Page for A Digital Business Idea
5/27/20-5/29/20
<hr>
Demos of your business idea can help get investors and collaborators on board. With a little bit of css, html, and Photoshop knowledge, you can make a professional looking visual demo MPV in a short time.

### 1. Pick A Template SIte
I created a demo application of my business idea from an already existing site, which I used as a template. 

Find a website that is similar in structure to your idea. For example, if you were creating a site for renting out your pets to play with, you might use AirBnb's website as your template. You can easily replace the rental spaces with pets, so it's a good match.

### 2. Save The Page(s) as An HTML
Use the chrome extension [Save Page WE](https://chrome.google.com/webstore/detail/save-page-we/dhhpefjklgkmgeafimnjhojgjamoafof) to save a complete web page (as currently displayed) as a single HTML file that can be opened in any browser.

### 3. Edit The Page

Once you have the page(s) saved, open in VSC code and edit the css and html. Use DevTools to help figure out what to change. 

Your site will be unusable. But it will create a visual prototype. 

 Where applicable, replace the images on the site with images you saved from Google or Instagram. You don't have to pay for images because you're not publishing this website. 

You can customize images further on Photoshop or another image editor.

### My Demo

For my site, I used Fiverr as the template. Fiverr was a great template for my idea which will be a market place for a type of product.

<img src="log_imgs/template_site_5-29-20.png">

As you can see, I copied some of Fiverr's design elements directly. But that's ok. The purpose of making this mock-up is to demonstrate my business idea to collaborators. The mock-up is not a template for the exact design and branding. 

I blurred the text for this post, but collaborators will understand the business from the text and visuals.

### Machine Learning 
05/22/20
<hr>

### Getting Started
[Your First Machine Learning Project in Python Step-By-Step](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/)

### Install Python
>**Don’t Update** Python 2.x to Python 3.x, Just **Install** Python 3.x on the Mac

-from [How to Install Updated Python 3 on Mac](https://osxdaily.com/2018/06/13/how-install-update-python-3x-mac/)

Use the macOS 64-bit installer which you can [download here](https://www.python.org/downloads/release/python-383/)

>If you're using macOS go to Macintosh HD > Applications > Python3.6 folder (or whatever version of python you're using) > double click on "Install Certificates.command" file.

-from [Stackoverflow](https://stackoverflow.com/questions/50236117/scraping-ssl-certificate-verify-failed-error-for-http-en-wikipedia-org)

### Install pip
[Installating Pip](https://pip.pypa.io/en/stable/installing/):

Run:
```bash
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
```
Then `pip install`:
- scipy
- numpy
- matplotlib
- pandas
- sklearn



### Optimizing WordPress Speed With GoDaddy cPanel Shared Hosting 
05/10/20 - 05/20/20
<hr>

Jump to my [**Conclusion**](#wp-optimization-conclusion) to see what I did.

<hr>

#### Wordpress Speed Optimization resources
- [GTmetrix](https://gtmetrix.com/)- Gives you speed metrics on your site
- [Speed Up WordPress in 2019: How To Optimize Your Website & Make It Load Fast](https://www.youtube.com/watch?v=ATXACFtcyKs)
- [Optimizing MP4 Video for Fast Streaming](https://rigor.com/blog/optimizing-mp4-video-for-fast-streaming)
  - [HandBrake](https://handbrake.fr/) *Free software for optimizing mp4 videos*
- [How to Read a Waterfall Chart for Beginners](https://gtmetrix.com/blog/how-to-read-a-waterfall-chart-for-beginners/)
- [How To Fix GoDaddy’s Slow WordPress Hosting Using An Array Of Tools + Plugins (And How To Check If Your GoDaddy Server Is Slow)](https://onlinemediamasters.com/slow-wordpress-hosting-godaddy/)- Text companion of below
- [How To Fix Slow WordPress Site On Godaddy](https://www.youtube.com/watch?v=vXgIVbcvGiw)- Video companion of above
  - [Steps 3-5: Configure WP Fastest Cache or W3 Total Cache Plugin](https://www.youtube.com/watch?v=vXgIVbcvGiw&t=560s)
  - [Step 6: Clean Up Database With WP-Optimize](https://www.youtube.com/watch?v=vXgIVbcvGiw&t=1099s)
  - [Step 7: Defer Parsing Of JavaScript](https://www.youtube.com/watch?v=vXgIVbcvGiw&t=1142s)
    - This step didn't change anything. I still have a .js file parsing during initial page load: *wp-content/cache/wpfc-minified/a0uy3y/47yt4.js*
- [Why is my page slow?](https://gtmetrix.com/why-is-my-page-slow.html)
  - [Page Caching](https://gtmetrix.com/why-is-my-page-slow.html#page-caching)
- [Static site generators vs. caching](https://stitcher.io/blog/static_sites_vs_caching)
- [PageSpeed and YSlow are Half the Battle](https://gtmetrix.com/blog/pagespeed-and-yslow-are-half-the-battle/)- Frontend vs. Backend
- [WordPress Speed Optimization - How I Got 100% GTmetrix Scores](https://www.youtube.com/watch?v=JZVaeJwp7Zs)
  - [Optimize External Resources](https://www.youtube.com/watch?v=JZVaeJwp7Zs&t=1687s)

<h3 id="minimize-redirects"></h3>

### Minimize Redirects

If you're using GoDaddy cPanel hosting, you may have a weird redirect- "`https://img.secureserver.net......`" This is from the monitoring script that GoDaddy puts into your webpage. It helps GoDaddy collect data on how your site is working. But that data is just for them. You don't need it. The redirect slows down your site. So this is how to delete it.
  - while logged in to GoDaddy, go to [your hosting](https://myh.godaddy.com/#/hosting/all)
  - click on your **site name**
  - At the top click **GoDaddy Analytics** *or* add `/godaddyAnalytics` to your current URL address
  - Click "`No, I don't want to participate in the program.`" and **Confirm**.
  
Keep in mind, GoDaddy is always changing their site. So you may have to navigate the site differently to find the opt-out.

<h3 id="wpfc-settings"></h3>

### Wp-Fastest Cache Settings:

>If you plan on using neither *[Cloudflare nor StackPath]*, use the settings below. The only thing you would change is in the Preload tab (pages per minute). If you’re on shared hosting use 4-6, VPS should use 10-12.

*from [Online Media Masters](https://onlinemediamasters.com/wp-fastest-cache-settings/)*

![](https://v9n9s3j3.stackpathcdn.com/wp-content/uploads/2016/11/WP-Fastest-Cache-Settings-1.png)

### Clear Cookies

Remember to clear your site data if you're getting a different waterfall in DevTools than GTmetrix. I was still getting an old css file on Chrome, not the cached minified version.

#### Clear Cookies in Chrome:

1. **Menu Bar** -> **Chrome** -> **Preferences**
2. scroll to **Privacy and security** -> **Site Settings** -> **View permissions and data stored across sites** 
3. In **Sort by** search your site name.
4. Click on the three **vertical dots** across from your site name
5. **Clear data**


## Stuck on Defer Parsing Javascript

[How to Defer Parsing of JavaScript Properly](https://technumero.com/defer-parsing-of-javascript/)

[My forum post about Defer Parsing Javascript](https://wordpress.org/support/topic/defer-javascript-parsing/)

I can't figure out how to defer parsing of javascript with the Primer theme. I'm able to defer parsing of javascript with other themes.

I tried several methods:
1. I’ve tried a few plugins
2. I tried adding this to header.php:

   ```php
   <?php //php tag added only for github markdown.
   if (!(is_admin() )) {
   function defer_parsing_of_js ( $url ) {
   if ( FALSE === strpos( $url, '.js' ) ) return $url;
   if ( strpos( $url, 'jquery.js' ) ) return $url;
   // return "$url' defer ";
   return "$url' defer onload='";
   }
   add_filter( 'clean_url', 'defer_parsing_of_js', 11, 1 );
   }
   ?>
   ```

3. I tried adding this to functions.php and replacing with the correct URL.
   ```html
   <script type="text/javascript">
   function parseJSAtOnload() {
   var element = document.createElement("script");
   element.src = "somejavascriptfiles.js";
   document.body.appendChild(element);
   }
   if (window.addEventListener)
   window.addEventListener("load", parseJSAtOnload, false);
   else if (window.attachEvent)
   window.attachEvent("onload", parseJSAtOnload);
   else window.onload = parseJSAtOnload;
   </script>
     ```
I’m using Stout, a Primer child theme. But even with just Primer I get this issue. Though I did not try the plugin method with just Primer. The issue goes away when I change to the Twenty Twenty theme.

**Solution:** The theme wasn't the issue. WP Fastest Cache was the issue. See my [conclusion](#wp-optimization-conclusion) for solution.

<h3 id= "wp-optimization-conclusion"></h3>

## Conclusion: Steps To Speed Optimize My WordPress on GoDaddy

<hr>

[*GTmetrix Scores*](https://gtmetrix.com/reports/dashiellbarkhuss.com/LQNxP4WT) **Before**:

<img src="log_imgs/start-scores_5-19-20.png"/>


  
[*GTmetrix Scores*](https://gtmetrix.com/reports/dashiellbarkhuss.com/Cnasj9u9) **After**:
<img src="log_imgs/end-scores_5-20-20.png"/>

*No money spent.*

### 1. Add These Free Plugins

<hr>

1. [Self-Hosted Google Fonts](https://wordpress.org/plugins/selfhost-google-fonts/)
   - Video: [WordPress Speed Optimization: Optimize External Resources: Google Fonts section](https://youtu.be/JZVaeJwp7Zs?t=1727)
2. [WP-Optimize](https://wordpress.org/plugins/wp-optimize/)
   - Video: [Step 6: Clean Up Database With WP-Optimize](https://www.youtube.com/watch?v=vXgIVbcvGiw&t=1099s)
3. [WP Fastest Cache](https://wordpress.org/plugins/wp-fastest-cache/)
   - Article: [Online Media Masters: WP Fastest Cache Settings](https://onlinemediamasters.com/wp-fastest-cache-settings/)
   - Video: [Steps 3-5: Configure WP Fastest Cache or W3 Total Cache Plugin](https://www.youtube.com/watch?v=vXgIVbcvGiw&t=560s)-Online Media Masters
4. [Asset CleanUp](https://wordpress.org/plugins/wp-asset-clean-up/)
   - Video: [Speed Up WordPress in 2019: Asset CleanUp section](https://youtu.be/ATXACFtcyKs?t=778)

### 2. Defer Parsing of Javascript
<hr>

*Article on **why** & **how**:* [How to Defer Parsing of JavaScript Properly](https://technumero.com/defer-parsing-of-javascript/)

*Video on **how**:* [Step 7: Defer Parsing Of JavaScript](https://www.youtube.com/watch?v=vXgIVbcvGiw&t=1142s)

**How:**

Add this to the end of `functions.php`. I added it to my parent theme. But maybe it would also work if you add it to a child theme.
```php
<?php //php tag added only for github markdown.
function defer_parsing_of_js( $url ) {

     if ( is_user_logged_in() ) return $url; //don't break WP Admin
     if ( FALSE === strpos( $url, '.js' ) ) return $url;
     if ( strpos( $url, 'jquery.js' ) ) return $url;
     return str_replace( ' src', ' defer src', $url );
}
add_filter( 'script_loader_tag', 'defer_parsing_of_js', 10 );
?>
```

If you have users on your site outside of admins, you might want to change the `is_user_logged_in()` code to one of the wordpress functions that tells if an admin is logged in.

#### **A note on WP Fastest Cache\*\*
<h3 id= "wpfc-defer"></h3>

Using WP Fastest Cache with [these settings](#wpfc-settings), WP Fastest Cache creates a *combined js* file. To defer this file, you'll need to do ***extra coding***.

WP Fastest Cache bypasses the core WordPress hooks. So WP Fastest Cache ignores the above php code[(*source*)](https://wordpress.org/support/topic/how-to-defer-javascript-when-the-tag-of-enqueued-script-has-two-src-urls/#post-12857234).

<h3 id ="wpfc-defer-update"></h3>

***UPDATE/WARNING**: While the solution below worked to defer the file, it broke my site. After the first load, my site looked fine. But upon refreshing with browser-caching enable, my hero image and video looked strange. I deleted this tweak in my code. Still, the code might help you, so here it is.*

**Defer the WP Fastest Cache combined js script:** Add "`defer`" to the code that generates the script tag. Remember to change this whenever you update the plugin.

*Line 240, wp-content/plugins/wp-fastest-cache/inc/js-ulilities.php*:
```php
<?php //php tag added only for github markdown.
$newLink = "<script defer src='".$jsLink."/".$jsFiles[0]."' type=\"text/javascript\"></script>";
?>
```
#### Premium Cache Plugin $$$
If this workaround doesn't suite you, WP Fastest Cache *Premium* can do this at the click of a button. However, [Online Media Masters recommends](https://onlinemediamasters.com/wp-fastest-cache-settings/) WP Rocket if you are going to pay for premium.
> Is WP Fastest Cache Premium worth it?
>
>If you're going to spend money on a premium cache plugin, most people use WP Rocket since it comes with more features than WP Fastest Cache Premium and will typically yield better results.

Of course, if you love quality, saving money, and have questionable morals you can try to get the torrent for the plugin. I don't judge! Especially because I tried to do that myself but had trouble getting the torrent to work.


WP Fastest Cache Premium costs a one time payment of $49.99. The pricing for WP Rocket is more confusing- it seems like it would come out more expensive.

### 3. Optimize Images & Videos
<hr>

To **optimize images**:
  - Video: [Speed Up WordPress in 2019: Optimizing & Compressing Images](https://www.youtube.com/watch?v=ATXACFtcyKs&t=1207s)

**Another resource** I haven't watched. It covers- Serve Scaled images, Specify Image Dimensions, and Lossless Compression:
  - Video: [WordPress Speed Optimization: Optimize Images](https://youtu.be/JZVaeJwp7Zs?t=1336)

I **optimized my video** by using [HandBrake](https://handbrake.fr/)- *free software for optimizing mp4 videos.* More info:

   - Article: [Optimizing MP4 Video for Fast Streaming](https://rigor.com/blog/optimizing-mp4-video-for-fast-streaming)


### 4. Remove GoDaddy Redirect
<hr>

If you're using GoDaddy cPanel hosting, you may have a weird redirect- "`https://img.secureserver.net......`" in your waterfall. 

[Here's](#minimize-redirects) how to fix it.


### 5. What's left
<hr>

#### GTmetrix Recommendations:
At the end, I had 3 recommendations on GTmetrix lower than 99%:
1. Defer parsing of JavaScript **93%**
2. Use a Content Delivery Network (CDN) **0%**
3. Make fewer HTTP requests **84%**

#### 1. Defer parsing of JavaScript
This was addressed [here](#wpfc-defer-update).

#### 2. Use a Content Delivery Network (CDN)
This costs money so I'm skipping it.

#### 3. Make fewer HTTP requests

The free WP Fastest Cache [doesn't combine footer js files.](https://wordpress.org/support/topic/wp-fastest-cache-dont-combine-javascript-after-install-clearfry-and-deleting-it#post-11295205) That's left me with 7 external Javascript scripts. 


##### Possible solutions
1. Try other plugins
2. WP Fastest Cache Premium
3. Edit WP Fastest Cache free

If I were to edit WP Fastest Cache free, I would look at the code below. This code deals with javascript scripts in the header *(head? whats the difference?)*. But it could be modified to include the scripts in the footer.

*Line 736, wp-content/plugins/wp-fastest-cache/inc/cache.php*:
```php
<?php //php tag added only for github markdown.
if(isset($this->options->wpFastestCacheCombineJs)){

$head_new = $this->get_header($content);

if($head_new){
if(isset($this->options->wpFastestCacheMinifyJs) && $this->options->wpFastestCacheMinifyJs){
$js = new JsUtilities($this, $head_new, true);
}else{
$js = new JsUtilities($this, $head_new);
}

$tmp_head = $js->combine_js();

$content = str_replace($head_new, $tmp_head, $content);

unset($r);
unset($js);
unset($tmp_head);
unset($head_new);
 }
}
?>
```
I'm no WordPress/php expert. So it doesn't seem worth my time atm. Paying for premium is starting to sound good.

#### Hosting:
I'm using GoDaddy's cPanel shared hosting. Apparently, it's not known for speed. So I might switching to a different host. I've heard SiteGround is a good option.


### More Steps For You
<hr>

There may be more steps you need to take depending on your GTmetrix recommendations that are different than mine. Here are some good resources on optimizing your WordPress.

-  **Video**: [Speed Up WordPress in 2019: How To Optimize Your Website & Make It Load Fast](https://www.youtube.com/watch?v=ATXACFtcyKs) 
- **Text**: [How To Fix GoDaddy’s Slow WordPress Hosting Using An Array Of Tools + Plugins (And How To Check If Your GoDaddy Server Is Slow)](https://onlinemediamasters.com/slow-wordpress-hosting-godaddy/)
-  **Video**: [How To Fix Slow WordPress Site On Godaddy](https://www.youtube.com/watch?v=vXgIVbcvGiw)
- **Video**: [WordPress Speed Optimization - How I Got 100% GTmetrix Scores](https://www.youtube.com/watch?v=JZVaeJwp7Zs) 
  
- [More resources I used.](#wordpress-optimization-resources)

### 05/10/20
#### LED Resource
- [Ultimate Guide to Connecting LED Light Strips to Arduino](https://www.makeuseof.com/tag/connect-led-light-strips-arduino/)
  
### 05/04/20

## Lucid Dream Home Lab Update
I've been working on the [lab](#lab-explanation) and I have made a lot of progress. Today, I'm going to share just one part of the lab: **sending a text message with your eyes in morse code**.

## Texting With Eye Movements
  <img src="log_imgs/eyes_messaging_5-4-20.gif" width= 100%>

  <img src="log_imgs/mesage _sent_5-4-20.gif" width= 100%>

### Hardware:

 * [Heart and Brain SpikerShield Bundle](https://backyardbrains.com/products/heartandbrainspikershieldbundle) 

    - *discontinued.* An alternative option might be a [Ganglion from OpenBCI](https://shop.openbci.com/collections/frontpage/products/ganglion-board?variant=13461804483) 

Since the [Heart and Brain SpikerShield Bundle](https://backyardbrains.com/products/heartandbrainspikershieldbundle) is discontinued I would like to redo this with [OpenBCI](https://www.openbci.com/) in the near future. But, if you are up for it, you can try to adapt this project using an OpenBCI product on your own.

### How It Works
1. The subject wears electrodes connected to the hardware and signals in morse code. 
   - Looking left is akin to pressing down the telegraph button. Looking right is akin to releasing the button.
   - Holding your eyes left for 4 or more seconds and then looking right, means "send the message"
   - Holding your eyes right for 4 or more seconds and then looking left, means "I f**ked up! Delete the message so far."
2. The electrodes send data to the arduino program
3. The arduino program interprets the data. 
   1. It figures out which data means the eye moved left or right. 
   2. It converts the eye movements to morse code.
   3. It converts morse code to English. 
   4. It serial prints the message with the delimiter 'SND'.
4. The node program watches the serial port for data from the arduino. Once it sees the delimeter 'SND' it recieves the message. It then executes a bash file with the message.
5. The bash file takes the message and sends it to whomever is named "Mom" in your contacts. This only works if you have Messages app and a Mac I believe. 

### EOG
The hardware uses [EOG](https://en.wikipedia.org/wiki/Electrooculography). EOG records eye movement. Electrodes are placed on the outer edges of the eyes. The back of your eye has more electrical activity than the front (Don't quote me). So when you look left, the backs of your eyes are closer to the right electrode. And further from the left electrode. So the electrodes can sense a change occurred.

You get a bunch of data from the electrodes in the form of numbers from 1-1024 when you **analogRead()** the input stream in Arduino.

This is what the data looks like when mapped out visually over time.

<img src="log_imgs/eye_vs_clench_-5-4-20.png" width="100%">

Clenching also affects the data. So in the code we detect jaw clenching but ignore it.  

*One thing isn't clear from the graph:*

You might think that if you hold your eye to the left, the peak will stay up and span a wider distance in the graph. But no. It will drop back down to the middle range immediately, regardless of how long you look left. If we want to know how long the eye stayed looking left, we look for a dip downward. That means the eye has move right, away from the left position it just occupied.

## Heart and Brain SpikerShield Setup

The alligator clip with the pink wire goes on the left side of your eyes. The red wire goes on the right side of your eyes. The black wire goes on your mastoid process. More info [here](https://backyardbrains.com/experiments/EOG)

### Arduino Code

```arduino

#define EOG A0

//Eye movement Variables

const int bufferSize = 20;
const int highThreshold = 600;
const int lowThreshold = 422;
int readingsBuffer[bufferSize]; //last readings

bool lastSignalWasLeft; //We must store that the last signal was left. 
                        //multiple "lefts" will get processed unless we tell 
                        //the sketch to ignore the signal once we know what it is
bool lastSignalWasRight; //^same for right


//Morse code Variables

unsigned long morseBitBase = 800 ; //morse bit length, you can change this to be longer or shorter depending on your morse code speed
unsigned long wiggleRoom = 0; //aka tolerance- you can add some extra milliseconds to account for accodentally going slower.

unsigned long morseBit = morseBitBase + wiggleRoom;
unsigned long morse3Bit = (morseBit *3) +wiggleRoom;


bool subjectStartedSignaling = false;

String subjectsMorseCode = "";

enum morseState {
  NEW_INTRA_CHARACTER,
  NEW_CHARACTER,
  NEW_WORD,
  NEW_MESSAGE //message variable
};

enum morseState currentMorseState = NEW_INTRA_CHARACTER;


unsigned long lastSignalChangeAt;
bool lastSignal;
unsigned long clearGapLength = morseBit*5 +wiggleRoom; //message variable 
unsigned long sendBeepLength = morseBit*5 +wiggleRoom; //message variable


//message variables
String delimeter = "SND";

String message = "";



void setup() {
  Serial.begin(115200);
}

void loop() {
   int reading = analogRead(EOG);
   unsigned long now = millis();
   updateReadingsBuffer(reading);

    //---------------determine if the last analogRead signals was an eye movement---------------------
 
   String eog = determineEOGSignal(); //returns string "Left", "Right", "Jaw", "Normal"
   bool eyeMovementDetected = eog == "Right" || eog == "Left";

  //------------------------------Morse Code------------------------------
    if (eyeMovementDetected){ 

                if (!subjectStartedSignaling) {
 
                    subjectStartedSignaling = true; 

                } else {

                  unsigned long signalLength = now-lastSignalChangeAt;
                  char morseIntraChar = signalToMorse(signalLength, lastSignal);
           
/////////////////////////////////////////////////////////////
//         All of the Serial.print's need to be commented out 
//         when you are actually sending this to node 
//         except for 'Serial.println(message +"SND");'
//         However, they can be helpful for depugging.
//         So I am leaving them in, commented out.
//////////////////////////////////////////////////////////////

//                Serial.print("subjectsMorseCode: '");Serial.print(subjectsMorseCode);Serial.println("'");
            
                  if (morseIntraChar != 'g' && morseIntraChar != '*' && morseIntraChar != 'S'){
                    subjectsMorseCode.concat(morseIntraChar);
                  } else if (morseIntraChar == 'S'){
                    Serial.println(message +"SND");
                    message = "";
                    subjectsMorseCode ="";
                  } else if (morseIntraChar != '*' && morseIntraChar != 'S'){
                      if (currentMorseState == NEW_CHARACTER || currentMorseState == NEW_WORD){
  
                          char engChar = morseToEnglishChar(subjectsMorseCode);
//                          if (engChar=='*')Serial.print("error, wrong input: "+subjectsMorseCode);
//                          Serial.print(" char: ");
//                          Serial.println(engChar);
                          
                          if (engChar!='*'){
                            if(currentMorseState == NEW_WORD) message.concat(" ");
                            message.concat(engChar); 
//  
//                            Serial.print("message pending: ");
//                            Serial.println(message);
                          }
                          subjectsMorseCode ="";
                      } else if (currentMorseState == NEW_MESSAGE){
                        message = "";
                        subjectsMorseCode ="";
//                         Serial.print("cleared message pending: ");
//                          Serial.println(message);
                      }
                  }
                }
                          
          lastSignalChangeAt = now;
          lastSignal = eog == "Right" ? 0 : 1;
        }


} //==========end void loop========

//===============================Eye Movement Interpretation functions=========================
void updateReadingsBuffer(int reading){    
  for(int i = 0; i < bufferSize-1; i++)
    {
      readingsBuffer[i] = readingsBuffer[i+1];
    }
  readingsBuffer[bufferSize-1] = reading;

}

String determineEOGSignal(){
    int reading = readingsBuffer[bufferSize-1];

    String determinedSignal;

        if(!isNormal(reading)){

        // what is the signal?
           if(signalIsJawClench(readingsBuffer)){
              determinedSignal = "Jaw"; //your jaw clenched

            } else if(signalIsEyeLeft(readingsBuffer) && !lastSignalWasLeft){
              lastSignalWasLeft = true;
              lastSignalWasRight = false;
              determinedSignal = "Left";

            } else if(signalIsEyeRight(readingsBuffer) && !lastSignalWasRight){
              lastSignalWasRight = true;
              lastSignalWasLeft = false;
              determinedSignal = "Right";
              
            } else {
              determinedSignal = "Normal";
            }

        } else {
              determinedSignal = "Normal";
        }
    return determinedSignal;
}

bool isNormal(int reading){ if (reading > lowThreshold && reading < highThreshold) {return true;}else{return false;}; }; 

bool isHigh(int reading){ if (reading > highThreshold) {return true;}else{return false;}; };
bool isLow(int reading){ if (reading < lowThreshold) {return true;}else{return false;}; };

bool signalIsJawClench(int readings[bufferSize]){
    for(int i = 0; i < bufferSize; i++)
    {
      if(isHigh(readings[i])){ //if any reading is high
          for(int i2 = i; i2 < bufferSize-i; i2++){
            if(isLow(readings[i2])){ // and any proceeding reading is low
                return true;
              }
          }
        }
      if(isLow(readings[i])){ //if any reading is Low
        for(int i2 = i; i2 < bufferSize-i; i2++){
          if(isHigh(readings[i2])){ // and any proceeding reading is HIgh
              return true;
            }
        }
      }
    }
      return false; 
}

bool signalIsEyeRight(int readings[bufferSize]){
    for(int i = 0; i < bufferSize; i++){
        if(!isHigh(readings[i])){
          return false;
        }
    }
    return true;
}

bool signalIsEyeLeft(int readings[bufferSize]){
    for(int i = 0; i < bufferSize; i++){
        if(!isLow(readings[i])){
          return false;
        }
    }
    return true;
      
}

//=============================Morse Code Interpretation functions===================================

char signalToMorse(unsigned long signalLength, bool signalType ){
  char morse;
    if(signalType){
      morse = interpretBeep(signalLength);
    } else {
      manageMorseState (signalLength);
      morse = 'g'; //gap
    }

    return morse;
}

char interpretBeep (unsigned long millisBeep){
  char meaningOfBeep;
  if ( millisBeep >= 100 && millisBeep <= morseBit){ 
    meaningOfBeep = '.';
  }  else if ( millisBeep > morseBit && millisBeep < sendBeepLength){  
    meaningOfBeep = '-';
  }else if ( millisBeep >= sendBeepLength){  
    meaningOfBeep = 'S'; //means "SEND"
  } else {
    meaningOfBeep = '*'; //means noise- ignore
  }

  return meaningOfBeep;
}

void manageMorseState (unsigned long millisGap){  
  if ( millisGap < 100 ){
      return; //noise
  } else if ( millisGap >= 100 && millisGap <= morseBit){ 
    currentMorseState = NEW_INTRA_CHARACTER;
  }  else if ( millisGap >= morseBit && millisGap < morse3Bit){ 
    currentMorseState = NEW_CHARACTER;
  } else if ( millisGap > morse3Bit && millisGap < clearGapLength ){ 
      currentMorseState = NEW_WORD;
  }  else if ( millisGap > clearGapLength ){ 
      currentMorseState = NEW_MESSAGE; //aka clear last message
  }
}

char morseToEnglishChar(String morse)
{
//Serial.print("morse code: ");
//Serial.println(morse);

  static String letters[] = {".-", "-...", "-.-.", "-..", ".", "..-.", "--.", "....", "..", ".---", "-.-", ".-..", "--", "-.", "---", ".--.", "--.-",
                             ".-.", "...", "-", "..-", "...-", ".--", "-..-", "-.--", "--..", "E"
                            };
  int i = 0;
  char englishChar;

    if (morse == ".-.-.-")
    {
      englishChar = '.';        //for break
    }
    else if (morse == ".-.-.--")
    {
      englishChar = '!';        //for !
    } else if (morse == "..--..")
    {
      englishChar = '?';        //for ?
    }
    else
    {
      while (letters[i] != "E")  //loop for comparing input code with letters array
      {
        if (letters[i] == morse)
        {
          englishChar = (char('A' + i));
          break;
        }
        i++;
      }
      if (letters[i] == "E")
      {
        englishChar = '*';  //if input code doesn't match any letter, error
      }
    }

  return englishChar;                            
}
```

### Node.js Code

More info [here](https://medium.com/@machadogj/arduino-and-node-js-via-serial-port-bcf9691fab6a)

```node
const SerialPort = require('serialport');
const Readline = require('@serialport/parser-readline');
const shell = require('shelljs');

const port = new SerialPort('/dev/cu.usbmodem14101', { baudRate: 115200 });
const parser = port.pipe(new Readline({ delimiter: 'SND' }));
// Read the port data
port.on("open", () => {
  console.log('serial port open');
});
parser.on('data', data =>{
  console.log('got word from arduino:', data);

  shell.exec('./message "'+data+'-this message was sent to you by eye movements" "Mom"');
});
```
You need to `npm install shelljs` and `npm install serialport`.

## Bash File 

```bash
!#/bin/bash

MSG=${1?Error:no message}
CONTACT=${2?Error:no contact provided}

osascript -e 'tell application "Messages" to send "'"${MSG/\"/\\\"}"'" to buddy "'"${CONTACT//\"/\\\"}"'"'
```

You need change the permissions to allow the script to be executable for the user with `chmod +x filename` and you need use the correct bash interpreter location after the shebang (`!#`). More info [here](https://www.taniarascia.com/how-to-create-and-use-bash-scripts/).

## Wrap Up

So that's a quick overview. I hope to do a more thorough tutorial in the future. But I wanted to push this out soon for those who are curious.
### 04/05/20
I haven't been logging much. I'm trying to take a different approach. That being- *Don't talk about a project until it's complete.* It helps motivate me to finish the project. Also, logging slows me down. 

But I wanted to post some updates here.

<h3 id="lab-explanation"></h3>

## Lucid Dream Home Lab 
I'm currently building a lucid dream lab the will induce lucid dreams and enable a user to communicate from a lucid dream to the outside world. I started this project in 2012. But it's been an on and off adventure.

After participating in a lucid dream study at Northwestern, I was inspired to revisit the project and add some features that Northwestern had.

## Alpha Detection
Yesterday, I finished creating an alpha brain wave detector. This will be involved in detecting when a person is in REM from EEG data.

  <img src="log_imgs/alpha_4-5-20.gif" width= 100%>

I did a lot of research on brain waves and signal filtering. I won't post all of that here. The info I got was mostly on Youtube. But here is the paramount video that helped me signal process the alpha waves:

[My Weekend Project: Audio Frequency Detector Using An Arduino](https://www.youtube.com/watch?v=wbeV0J30LGQ)

The only relevant part is the section on the code. For hardware, I'm going a different route- using the [Backyard Brains Heart and Brain SpikerShield](https://backyardbrains.com/products/heartandbrainspikershieldbundle). I followed their tutorial [Experiment: EEG-Record from the Human Brain](https://backyardbrains.com/experiments/EEG). I combined this Backyard Brains tutorial with the Youtube [Audio Frequency Detector](https://www.youtube.com/watch?v=wbeV0J30LGQ) tutorial in order to programmatically detect alpha waves.

## The Code

Though the project in the Youtube video detects audio frequency, it's pretty much the same for brain waves but the sampling frequency is different. 

```arduino
#include "arduinoFFT.h"
#define SAMPLES 128
#define SAMPLING_FREQUENCY 300

arduinoFFT FFT = arduinoFFT();
unsigned int samplingPeriod;
unsigned long microSeconds;

double vReal[SAMPLES];
double vImag[SAMPLES];


void setup() {
  // put your setup code here, to run once:
  Serial.begin(115200);
  samplingPeriod = round(1000000*(1.0/SAMPLING_FREQUENCY)); //PERIOD in microseconds


}

void loop() {
  for(int i=0; i<SAMPLES; i++){
    microSeconds= micros();
    
    vReal[i] = analogRead(0);
    vImag[i] = 0;

    while(micros()< (microSeconds + samplingPeriod)){
      
    }
  }

  FFT.Windowing(vReal, SAMPLES, FFT_WIN_TYP_HAMMING, FFT_FORWARD);
  FFT.Compute(vReal, vImag, SAMPLES, FFT_FORWARD);
  FFT.ComplexToMagnitude(vReal, vImag, SAMPLES);

  double peak = FFT.MajorPeak(vReal, SAMPLES, SAMPLING_FREQUENCY);
  
  if(peak<12 && peak >8){
    Serial.println("You have alpha waves of "+String(peak)+"hz. Your eyes must be closed."); 
  } else {
    Serial.println(String(peak)+"hz");
  }
}
```
Watch the tutorial to get an explanation of the code.

This project uses the library ardiunoFFT, which is a ***fast fourier transform*** library. Fourier transform is an algorithm that identifies frequencies from raw data. [Here's a great video explaining fourier transorm](https://www.youtube.com/watch?v=spUNpyF58BY).

Raw data will look like a bunch of numbers that, when mapped over time, will represent the waves. 

In my case, the electrodes glued to my head will *detect voltages from my brain*(don't quote me on this). Those numbers will look like this: 

**Example data:**
535
549
555
563
565
568
576
583
572
569
575
569
554
546
548
552
551
551
553
542 etc....

Each of these points of data occurred every 1 milliseconds. So you can map these numbers over time to get a visual idea of the waves:


  <img src="log_imgs/graph_eeg_4-5-20.png" width= 100%>

**Fourier transform** takes these numbers, and figures out the frequencies.

Let me know if you have any questions on Twitter [@DashBarkHuss](https://twitter.com/DashBarkHuss).

### 01/24/20
- ## Nutrition Project
  Yesterday we looked at daily values. Today I want to go through [my RDA's](https://health.gov/dietaryguidelines/2015/guidelines/appendix-7/) for my gender and age.

  Female 19-30 RDA's:

  **General:**
  - Energy: 1800 kcal
  - Water: 1500 g ---no RDA information

  **Vitamins**
  - B1 (Thiamine): 1.1 mg
  - B12 (Cobalamin): 2.4 μg
  - B2 (Riboflavin): 1.1 mg
  - B3 (Niacin): 14 mg
  - B5 (Pantothenic Acid): 10 mg ---no RDA information, cronometer put 5mg
  - B6 (Pyridoxine): 1.3 mg
  - Biotin: 300 μg ---no RDA information
  - Choline: 425 mg
  - Folate: 400 μg
  - Vitamin A: 700 mcg RAE ---cronometer put 2333 IU
  - Vitamin C: 75 mg
  - Vitamin D: 600 UI
  - Vitamin E: 15 mg
  - Vitamin K: 90 μg
  
  **Minerals**
  - Calcium: 1000 mg
  - Chromium: 120 μg ---no RDA information
  - Copper: 900 mcg
  - Iodine: 150 μg ---no RDA information
  - Iron: 18 mg
  - Magnesium: 310 mg
  - Manganese: 1.8 mg
  - Molybdenum: 75 μg ---no RDA information, cronometer put 45
  - Phosphorus: 700 mg 
  - Potassium: 4700 mg --cronometer put 2600
  - Selenium: 55 μg
  - Sodium: 2300 mg cronometer put 1500
  - Zinc: 8 mg

  **Carbohydrates**
  - Carbs: 130 g
  - Added Sugars: 10% of kcal
  - Fiber: 25.2 g

  **Lipids**
  - Fat: 20-35
  - Saturated Fat: 10% of kcal
  - Cholesterol: 300 mg  ---no RDA information

  **Protein**
  - Protein: 46 g

  ---no RDA information = number listed is cronometers DV's from yesterdays screenshots

  The macronutrients are of no importance to me. So let's disregard those.

  For my app, I'll just use what cronometer gave me for my micros.
  
  
### 01/23/20
- ## Nutrition Project
  I want to make something that has to do with nutrition density optimization. Nutrition density refers to the amount of micro nutrients per calorie.

  **Micronutrients**/**Calories**

  It's a not a specific measure, but it's used to describe foods. Organ meats are nutrient dense. Vegetables are generally more nutrient dense than fruits. Coconut oil is very low in nutrient density.

  Nutrient density isn't the "end all be all" to determining the best foods to eat, but it's a factor often over looked.

  **Macronutrients** include nutrients that provide calories: *fats*, *carbs*, and *protein*. **Micronutrients** are the vitamins and minerals.

  ## Daily Values
  I'll want to take note of the Daily Values for the USDA.

  Here are the **Daily Values** for a 2000 calorie diet according to the USDA, taken from Cronometer:

  **General:**
  - Energy: 2000 kcal
  - Water: 1500 g

  **Vitamins**
  - B1 (Thiamine): 1.5 mg
  - B12 (Cobalamin): 6 μg* 
  - B2 (Riboflavin): 1.7 mg
  - B3 (Niacin): 20 mg
  - B5 (Pantothenic Acid): 10 mg
  - B6 (Pyridoxine): 2 mg
  - Biotin: 300 μg
  - Choline: 550 mg
  - Folate: 400 μg
  - Vitamin A: 5000 IU*
  - Vitamin C: 60 mg
  - Vitamin D: 400 UI
  - Vitamin E: 20.13 mg
  - Vitamin K: 80 μg
  
  **Minerals**
  - Calcium: 1000 mg
  - Chromium: 120 μg
  - Copper: 2 mg
  - Iodine: 150 μg
  - Iron: 18 mg
  - Magnesium: 400 mg
  - Manganese: 2 mg
  - Molybdenum: 75 μg
  - Phosphorus: 1000 mg
  - Potassium: 3500 mg
  - Selenium: 70 μg
  - Sodium: 2400 mg
  - Zinc: 15 mg

  **Carbohydrates**
  - Carbs: 300 g
  - Added Sugars: 50 g
  - Fiber: 25 g

  **Lipids**
  - Fat: 65
  - Saturated Fat: 20 g
  - Cholesterol: 300 mg

  **Protein**
  - Protein: 50 g


  \* μ means micro, μg = micrograms

  \* IU means [International Unit](https://en.wikipedia.org/wiki/International_unit)

  To cross reference for accuracy, here's screenshots of Cronometer

  <img src="log_imgs/dv1_1-23-20.PNG" width= 45%>
  <img src="log_imgs/dv2_1-23-20.PNG" width= 45%>
  <img src="log_imgs/dv3_1-23-20.PNG" width= 45%>
  <img src="log_imgs/dv4_1-23-20.PNG" width= 45%>

  ## Daily Values vs Recommended Dietary Allotment

  **Daily Values** are on USDA labels. For example, we see above that the DV for **Vitamin C is 60 mg**. So if a food has 30 mg of vitamin C, you'll see *"Vitamin C 50%"* on the label.

  But Daily Values on labels are not the recommendations for everyone. The USDA has different Recommended Dietary Allowances (RDA) *"for your age, gender and life stage. These recommendations don't change based on your size."*[-Cronometer forum](https://forums.cronometer.com/discussion/1829/what-are-chronometers-daily-mirco-nutrient-targets-based-on)
  
  [More info on RDA's](https://www.ncbi.nlm.nih.gov/books/NBK114332/)

  

### 01/22/20
- ## React Native
  Two days ago I got my app onto a phone. But I noticed that it wasn't user friendly.

  The key pad that popped up was for letters. Mine should be for numbers. Adding `keyboardType="numeric"` or `keyboardType="phone-pad"` to the input tag fixed this.

  But then there was no return button. The return button is nice because it moved the cursor to the next input.

  <img width='45%' src = "log_imgs/return1_1-22-20.PNG">
  <img width='45%' src = "log_imgs/return_1-22-20.PNG">

  Another issue was that on some phones, the keyboard cuts the bottom buttons off.

### 01/13/20
- ## React Native
  My mom and sister went on weight watchers. I made a weight watchers calculator so they can figure out the points without paying for the app.
  
  I still need to style it nicely, and learn how to um *deploy*? *compile*? I don't know the correct term. But I need to put the app on their phones.

  <img width='200' src = "log_imgs/wwcalc_1-13-20.gif">

  Here's the app.js code:
  ```javascript
  /**
   * Sample React Native App
   * https://github.com/facebook/react-native
   *
   * @format
   * @flow
   */

  import React, { Component } from 'react';

  import {
    SafeAreaView,
    StyleSheet,
    TextInput,
    ScrollView,
    View,
    Text,
    StatusBar,
    Button,
  } from 'react-native';

  class App extends Component {

    constructor(){
      super()
      this.state = {
        cal: '',
        satFat:'',
        sugar:'',
        protein:'',
        points:''
      }
    }

    save(text, stateKey){
      this.state[stateKey] = text;
    }

    calculate(){
      let error=false;

      Object.keys(this.state).forEach(key=>{
          if (this.state[key]=='' && key!='points') error=true;
          console.log(error, this.state[key]);
      })
        
      if(error) return;
        const points = (this.state.cal * .0305) 
        + (this.state.satFat * .275) 
        + (this.state.sugar * .12) 
        - (this.state.protein * .098);
        
      this.setState({
            points
      })
    }
    clear(){
      this.setState({
        cal: '',
        satFat:'',
        sugar:'',
        protein:'',
        points:''
      })
    }
        
        render(){
          console.log('render', this)
          return (
            <View>
          <Text style={[styles.title]}>Weight Watchers Smart Points Calculator</Text>
          <Text style={[styles.label, styles.push]}>Calories:</Text>
          <TextInput style = {styles.input} onChangeText={(text)=>this.save(text, 'cal')}>{this.state.cal}</TextInput>
          <Text style={styles.label}>Saturated Fat:</Text>
          <TextInput style = {styles.input} onChangeText={(text)=>this.save(text, 'satFat')}>{this.state.satFat}</TextInput>
          <Text style={styles.label}>Sugar:</Text>
          <TextInput style = {styles.input} onChangeText={(text)=>this.save(text, 'sugar')}>{this.state.sugar}</TextInput>
          <Text style={styles.label}>Protein:</Text>
          <TextInput style = {styles.input} onChangeText={(text)=>this.save(text, 'protein')}>{this.state.protein}</TextInput>
          <Button style = {styles.button} onPress= {this.calculate.bind(this)} title="calc"></Button>
          <Button style = {styles.button} onPress= {this.clear.bind(this)} title="clear"></Button>
          <Text style={[styles.label, styles.push]}>Points:</Text>
          <Text style = {styles.points}>{this.state.points}</Text>
        </View>
    );
      }
  };

  const styles = StyleSheet.create({
    title:{
      marginTop:110,
      marginHorizontal: 20,
      fontSize:21,
      color: 'blue'
    },
    push:{
      marginTop:30
    },
    label:{
      color: 'red',
      borderColor: 'blue',
      marginHorizontal: 90,

    },
    input:{
      color: 'red',
      borderColor: 'blue',
      borderWidth:1,
      marginHorizontal: 90,
    },
    points:{
      color: 'red',

      marginHorizontal: 90
    },
    button:{
      marginTop:90,
      color: 'red',
      borderColor: 'blue',
      borderWidth:1
    }
  });

  export default App;
  ```
### 01/12/20
- ## Bot
  My bots been up and it's used no dyno hours. I'm not sure how this is possible. It might be becaus eI have it up as a worker now. But I thought I had it up that way before and the hours were still going down.
  
### 01/11/20
- ## Shell Scripting
  Yesterday, I wanted to get a boolean.

  I tried 
  ```bash
  echo [ u == u ]
  >> [ u == u ]
  ```

  It just returned the statement back to me. What's going on?

### 01/09/20
- ## Shell Scripting

  To set an env variable in the terminal:
  ```bash
  export var=value
  echo $var 
  >> value
  ```
  -*from [UNIX: Set Environment Variable](https://www.cyberciti.biz/faq/set-environment-variable-unix/)*

  Get A Substring:
  ```bash
  STRING="this is a string"
  POS=1
  LEN=3
  echo ${STRING:$POS:$LEN}   # his
  ```
  -*from [Basic String Operations](https://www.learnshell.org/en/Basic_String_Operations)*

  
### 01/08/20
I'm on Siesta Key on Vacation, so I've been taking a break from my regular coding, and learning some shell scripting! Let's learn some more!

- ## Shell Scripting
  
  [Heroku CLI Commands](https://devcenter.heroku.com/articles/heroku-cli-commands)

  I'm got these commands from [CLI commands for dyno management](https://devcenter.heroku.com/articles/dynos#cli-commands-for-dyno-management):

  ```bash
  //turn on a dyno
  heroku ps:scale worker=1 -a helpmecodebot

  //stop a dyno
  heroku ps:stop worker.1 -a helpmecodebot

  //see if your dyno is on
  heroku ps -a helpmecodebot
  ```

  I want to make a script that turns the dyno on and off depending on if computer is on or not.

### 01/07/20

- ## Shell Scripting
  ## 1st Tutorial
  I wanted to write a bash script in unix so I followed this tutorial: [How to make a simple bash script (Mac)](https://www.hastac.org/blogs/joe-cutajar/2015/04/21/how-make-simple-bash-script-mac)

  ## Terms
  I googled the difference between the terms: *terminal*, *bash*, *command line*, *console*, and *shell*. I use these terms interchangeably, which is probably incorrect.
  ## 2nd Tutorial
  Next, I looked at this   tutorial: [Quick guide to writing a bash script on the Mac/Linux command-line](http://omgenomics.com/writing-bash-script/). This one showed how to add variables to your script. The shebang line didn't work for me. I changed it to the shebang in the other tutorial above. 
  
  This second tutorial left out steps.  Like that you have to exit out of nano or add the variable in to the script. So, if you're new to command line, this second tutorial might be confusing.

  ## Open A File in VSC From Terminal

  First, make sure you set up VSC to work with the coomand line:
  >Correct way is to open Visual Studio Code and press `Ctrl+Shift+P` then type `install shell command`. At some point you should see an option come up that lets you install shell command, click it. Then open a new terminal window and type `code`.

  -*From [How To Open Visual Studio Code Using Terminal](https://askubuntu.com/questions/852076/how-to-open-visual-studio-code-using-terminal)*

  Then type in Terminal: 
  ```bash
  code myscript
  ```

  ## You Are Dreaming Script
  In my [lucid dream club meetups](https://www.meetup.com/Active-Dreaming-Group/), I like to make my computer tallk to people after I leave the room and make it tell them they are dreaming. I was doing this manually in the command line. Now, I wrote a script that I can use.

  ```bash
  #!/bin/bash

  FIRSTNAME=${1?Error:no first name given}
  LASTNAME=${2?Error:no last name given}

  sleep 17; say "Hello?"; 
  sleep 6; say "Hello"; 
  sleep 2; say "Hello, $FIRSTNAME."; 
  sleep 2; say "I have a message for you."; 
  sleep 1; say "Yes, You. $FIRSTNAME $LASTNAME"; 
  sleep 1; say "The message is this: You are dreaming, $FIRSTNAME. WAKE UP!"
  ```
  
  To call the function, you run this is the command line from the directory the script is in:

  ```bash
  code Shlomo Karbal
  ```



### 01/04/20

- ## React Native
  I'm trying to figure out how to change the black underlay to another color. 

  <img width=600 src="log_imgs/rnopac_1-4-20.GIF">

  Link to sample code: [Link](https://facebook.github.io/react-native/docs/touchablehighlight#onhideunderlay)

  [@adescode](https://twitter.com/adescode) on twitter helped me. Together we found this to be the answer:

  ```html
  <TouchableHighlight
          underlayColor='blue'>
  ```
  Add `underlayColor='<somecolor>'` to the `TouchableHighlight` tag.


### 01/03/20

- ## React Native
  I followed the instructions under the "***React Native CLI Quickstart***" tab on the page [Getting Started](https://facebook.github.io/react-native/docs/getting-started). This way, I can use modules that have native code. You can't with Expo.

  ## Linear Gradient
  Now I followed the instructions from the docs for [react-native-linear-gradient](https://www.npmjs.com/package/react-native-linear-gradient):

  >Add it to your project
  >
  >First, install it with `npm install react-native-linear-gradient --save`
  >
  >Then you can try to link the project automatically:
  >
  >`$ react-native link react-native-linear-gradient`

  I had to add `npx` to the second command: `npx react-native link react-native-linear-gradient` 

  This still gave me an error: something about `BVLinearGradient`. So I had to cd into `ios` and run `pod install`. That got rid of the error.

  <img width="200" src="log_imgs/gradient_1-3-20.PNG">

  Added to my project:

  <img width="200" src="log_imgs/app_1-3-20.PNG">


### 1/2/20

- ## React Native
  I'm having trouble. When I run `npm run ios` I got this:

  ```
  Invariant Violation: `<appName>` has not been registered. This can happen if: * Metro (the local dev server) is run from the wrong folder. Check if Metro is running, strop and restart it in the current project. A module failed to load due to an error and 'AppRegistry.registerComponent' wasn't called.
  ```

  I found that I had a terminal running so I closed it and tried again.

  But then I go this:

  ```
  No bundle URL present.
  
  Make sure you're running a packager server or have included a .jsbundle file in your application bundle.
  ```
  From [No Bundle URL Present](https://forums.raywenderlich.com/t/no-bundle-url-present/63018/9):

  >Before the step you’re asking about, you should have this code in the file:
  >
  >export default class App extends >`Component<{}> { 
     // A bunch of stuff
  }`
  >
  >Change the first line, so essentially you have:
  >
  >`class SearchPage extends Component<{}> {
  >  // A bunch of stuff
  >}`

  So I changed 
  ```javascript
  export default class App extends Component 
  ```
  To
  ```javascript
  class SearchPage extends Component
  ```
  Which gave me another error but then when I changed it back it somehow worked now. I don't know how that happened.

  ## Linking
  From the docs for [react-native-linear-gradient](https://www.npmjs.com/package/react-native-linear-gradient):

  >Add it to your project
  >
  >First, install it with `npm install react-native-linear-gradient --save`
  >
  >Then you can try to link the project automatically:
  >
  >`$ react-native link react-native-linear-gradient`

  This doesn't work for me. I get:
  ```bash
  bash: react-native: command not found
  ```

  Is this because I'm using Expo and I never installed the React Native CLI?

  How can you link with Expo?

  >You can't. It states this very clearly in [the docs](https://docs.expo.io/versions/latest/introduction/faq#what-is-the-difference-between-expo-and):
  >
  >>But no native modules…
  >>
  >>The most limiting thing about Expo is that you can’t add in your own native modules without detaching and using ExpoKit. Continue reading the next question for a full explanation.
  >
  >If you want to use anything that requires `react-native link`, then you need to [detach](https://docs.expo.io/versions/latest/expokit/detach) your project and then develop it [with or without ExpoKit](https://docs.expo.io/versions/latest/guides/expokit.html). You will lose certain features and integrations (off the top of my head, I think Push Notifications via Expo is one of them) when doing so, but that is the trade-off Expo provides as an all-in-one package. When detaching, you lose those features.
  
  *-from [react native link using expo?](https://stackoverflow.com/questions/44977693/react-native-link-using-expo)*

  So I guess I have to look into that!