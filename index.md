# 여우숲(하현달)

<body>

  역사상 가장 큰 실패였던, 대규모 프로젝트 "K-9"… 왜 실패했던걸까?
  <br><br>
  무더운 여름, 뻔한 공포게임은 치우죠. 여우숲으로 당신을 초대합니다 

  <img src = "images/Ex01.jpg" alt = "Example 001" style="display: block; margin: auto;">
  <span style="color: blue;">#공포#레이싱#퍼즐#스토리게임</span>
  
</body>


<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
  <div class="column is-four-fifths">
    <h2>작품 소개</h2>
    <div class="content has-text-justified">
     작품 소개 텍스트
    </div>
  </div>
</div>


<!-- Dataset Download Buttons -->

## SIDL Dataset 
We provide 80% of the scenes for training and learning. The remaining scenes are used for online evaluation.
### Patchify images (512x512)
For efficient training and learning, we provide patchified images. 
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <a class="button is-primary" href="https://drive.google.com/file/d/1es3rPo5Y9O96EjDVXanUY8NpaRprWH-h/view?usp=sharing" target="_blank">Train</a>
  <a class="button is-primary" href="https://drive.google.com/file/d/1u5-MDauO3XolXsU6eOARwlXo7SnpLwqA/view?usp=sharing" target="_blank">Validation</a>
  <a class="button is-primary" href="https://drive.google.com/file/d/1-SFyyjH0G3C68OfDjZ_O7M4mOqkcJdEf/view?usp=sharing" target="_blank">Test</a>
</div>

### Full-resolution images (4032x3024)
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <a class="button is-primary" href="https://drive.google.com/file/d/1s_gUw1DCqokihl3YtO3lu9_GnLZaSElI/view?usp=sharing" target="_blank">Train</a>
  <a class="button is-primary" href="https://drive.google.com/file/d/1OHxG8Jh0goKIhkJTe9NXZ6uIuD5qVaNH/view?usp=sharing" target="_blank">Validation</a>
</div>

### RAW files
We also provide RAW image files (DNG) along with metadata.
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <a class="button is-primary" href="https://drive.google.com/file/d/1k78IIsUl2eYPnPvWkBampU0qlMrW4F-u/view?usp=sharing" target="_blank">DNG images</a>
  <a class="button is-primary" href="https://drive.google.com/file/d/1lAab5F3jjCByY4OEvGSAfykyAqp2wfTi/view?usp=sharing" target="_blank">Metadata</a>
</div>

### Online Evaluation  
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <a class="button is-primary" href="http://203.253.25.170:8080" target="_blank">Click here to launch evaluation</a>
</div>  
Click the button above to evaluate your model on the SIDL benchmark.


### ISP pipeline
Coming soon


### Citation
<pre><code class="language-bibtex">
@inproceedings{choi2025sidl,
  title     = {SIDL: A Real-World Dataset for Restoring Smartphone Images with Dirty Lenses},
  author    = {Choi, Sooyoung and Park, Sungyong and Kim, Heewon},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence},
  volume    = {39},
  number    = {3},
  pages     = {2545--2554},
  year      = {2025}
}
</code></pre>

