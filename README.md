# LARF-CHI-EA-25
# Let AI Read First - Enhancing Reading Abilities for Individuals with Dyslexia through Artificial Intelligence(CHI 2025 Late Breaking Work)

[Sihang (Nagi) Zhao](https://akutagawa1998.github.io/), [Shoucong Xiong],[Bo Pang] [Xiaoying Tang], [Xiaoying Tang](https://sse.cuhk.edu.cn/en/faculty/tangxiaoying), [Pinjia He](https://pinjiahe.github.io/)
               
### [Paper]() | [Project Page](https://github.com/LARF2025/LARF-CHI-EA-25/)


![Teaser](figure_1.png)

## Software Demo: See the Releases
1. [For Windows](#Windows)
2. [For Linux](#Linux)
3. [For OSX](#OSX)

## Tips for OSX Install:
You may need to use the following instruction for installing the demo:
```
sudo spctl --master-disable
sudo codesign --force --deep --sign - /Applications/LARF.app
xattr -r -d com.apple.quarantine /Applications/LARF.app
```
After run the above instructions in the terminal, you should be able to start with LARF :)


### Tips for Model Selection:
1. Though our demo support different models, we strongly recommand you to use the model **LARGE THAN 13B** for better performance.
  Using small models like QWen 7B can lead to problems such as incorrect output (such as chaning the original textual information).
2. You need to set your own API in settings.

## License <a name="license"></a>

This project is under the MIT license. See [LICENSE](LICENSE) for details.

## Citation <a name="citation"></a>
Please consider citing our paper if you find this project helpful for your research:

```
```



## Acknowledgement <a name="acknowledgement"></a>
