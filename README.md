# GenAI BLIP

Bootstrapping Language-Image Pretraining (BLIP):  Leverages both text and image data to enhance AI models' understanding and generation of image descriptions.  It bridges the gap between natural language and visual content, or NLP & Computer Vision.

This Jupyter Notebook was created & run in Google Colab, using processors & models from Huggins Face. These open source platforms provide excellent "sandboxes" for exploring LLMs.  In this notebook, we used "Salesforce/blip-image-captioning-base" from Huggings Face.

First, we generated a caption for a personal photo.  Next, we generated condtional & unconditional captions for a sample photo from google, below.  The ability to respond to conditional captions varied.  For example:

1. text = "The weather in the picture is" Responce:  the weather in the picture is clear and sunny (Correct responce)
2. text = "The mood of the women in the picture is"  Responce:  the mood of the women in the picture is very attractive (Incorrect responce)

Additional fine tuning is needed to improve the accuracy of some of the responces.    

![Screen Shot 2024-07-08 at 11 33 08 AM](https://github.com/catherman/gen-ai-blip/assets/43255276/21c1b440-e885-4b1e-8b99-3aa061d306a1)





