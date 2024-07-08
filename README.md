# GenAI BLIP

Bootstrapping Language-Image Pretraining (BLIP):  Leverages both text and image data to enhance AI models' understanding and generation of image descriptions.  It bridges the gap between natural language and visual content, or NLP & Computer Vision.

For this, we used "Salesforce/blip-image-captioning-base" from Huggings Face.

We generated a caption for a personal photo.  We also generated condtional & unconditional captions for a sample photo.  The ability to respond to conditional captions varied.  For example:

1. text = "The weather in the picture is" Responce:  the weather in the picture is clear and sunny
2. text = "The mood of the women in the picture is"  Responce:  the mood of the women in the picture is very attractive

Additional fine tuning is needed to improve the responces.   

![Screen Shot 2024-07-08 at 11 33 08 AM](https://github.com/catherman/gen-ai-blip/assets/43255276/21c1b440-e885-4b1e-8b99-3aa061d306a1)





