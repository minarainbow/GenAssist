# [UIST 2023] GenAssist: Making Image Generation Accessible

This is the repository for annotated data and model for this paper: </br>

> Mina Huh, Yi-Hao Peng, Amy Pavel
>
> [GenAssist: Making Image Generation Accessible](https://dl.acm.org/doi/abs/10.1145/3586183.3606735).
>
> 🏆 Best Paper Award (top 1%)

✨ Check out our [website](https://minahuh.com/GenAssist) for examples and presentation!


# Abstract
Blind or low vision (BLV) creators use images to communicate with sighted audience members. 
However, creating or retrieving images remains challenging as it is difficult for BLV creators to use existing graphical authoring tools or assess image search results. 
Thus, creators describe their desired images to sighted people who create or retrieve the images or limit the types of images they create. 
While text-to-image generation models could let creators generate multiple high-fidelity images based on a text description (i.e. prompt), it is difficult to assess the content and quality of the generated image. 
We propose GenAssist, a system to make text-to-image generation accessible. 
Using our interface, creators can verify whether generated image candidates followed their prompt, access additional details added to the image but not specified in the prompt, and skim a summary of similarities and differences between image candidates. 
To power the interface, GenAssist uses a large language model to generate visual questions, vision-language models to extract answers, and a large language model to summarize the results. 
Our study with 12 BLV creators demonstrated that GenAssist enables and simplifies the process of image selection and generation, making visual authoring more user-friendly and accessible to all.

## Citation and contact
If you find our work helpful, please cite us as

```
@inproceedings{huh2023genassist,
  title={GenAssist: Making image generation accessible},
  author={Huh, Mina and Peng, Yi-Hao and Pavel, Amy},
  booktitle={Proceedings of the 36th Annual ACM Symposium on User Interface Software and Technology},
  pages={1--17},
  year={2023}
}
```

📧 Please contact Mina Huh at `minahuh[at]cs.utexas.edu` if you have any questions or suggestions.
