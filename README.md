# Welcome to ConceptsDreambooth!

I'm going to start this off with a huge thank you to the following brilliant scientists:

Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer

You can read their paper here: https://arxiv.org/abs/2112.10752

Nataniel Ruiz, Yuanzhen Li, Varun Jampani, Yael Pritch, Michael Rubinstein, Kfir Aberman

You can read their paper here: https://arxiv.org/abs/2208.12242

This resource wouldn't exist without their tireless work, so be sure to thank them! 

### Now you have refined power to train infinite artstyles!

I've put together this repo and corresponding Jupyter Notebook (ConceptsDreambooth_shanedeir.ipynb) in an effort to give you
a singular resource for easy training of any artstyle.

Included are several new contributions:

* Optimal Steps Formula
* Pre-Generated Artstyle Regularization Images
* Training Time Estimator (Very accurate)
* Cost to train calculator for Cloud Instances based on your rental price. 

# Setup

## Requirements:

At least 48GB of VRAM (The training uses 33.2GB, so if you have more than that, you're good')
At least 100 training images.
Some curiosity and excitement! 

## Getting started:

This guide is geared toward using vast.ai to train your artstyle.

While there are many platforms to rent a GPU, we suggest vast.ai or runpod.io

You're going to need at least $10(USD) to open a runpod account or $5(USD) to open a vast.ai account.

Make sure you rent an instance that fulfills the VRAM requirements set out above and is set to:

"On-Demand Pricing"

That way your training cannot be interrupted. 

## Step-By-Step

On vast.ai:

    Rent your instance, wait for it to start then click open.
    
    This loads your workspace.
    
    Now on the right hand sided select "new", then Python 3 (ipykernel).  
    
    This will load an empty Juptyer Notebook.
    
    In the box type: !git clone https://github.com/ShaneDeir/ConceptsDreambooth
    
    Now press the play button (or shift+enter).
    
    This will clone the repository onto your cloud instance. 
    
    Once it's finished, close the tab and go back to the workspace. 
    
    Select the folder called "ConceptsDreambooth". 
    
    Inside you'll see a file called ConceptsDreambooth_shanedeir.ipynb, open it. 
    
    Now all you have to do is follow the instructions in my Jupyter Noteboook!
    
    Great moves! Keep it up! 
    
    Important note: When you're finished with the cloud instance, be sure to stop it, then make sure you delete it as well. 
    That way you aren't charged money for an idling machine rental.
    

This readme will be updated with a video guide once we finish version 2 of ConceptsDreambooth! That way the video will stay relevant. 

Feel free to reach out me with any questions or suggestions! I'm happy to develop what you might find useful!
    
