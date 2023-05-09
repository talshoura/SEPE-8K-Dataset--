<a id="idtext"></a> 
# SEPE 8K Dataset Location
Please feel free to [**view and download the dataset here**](https://drive.google.com/drive/folders/1geFicEJeRD7dhmBlb0CHSQyrvIkYwp5Y?usp=sharing) \
For comments, feedback, or question please [Contact Us](mailto:Tariq.AlShoura@ucalgary.ca) at: [Tariq.AlShoura@ucalgary.ca](mailto:Tariq.AlShoura@ucalgary.ca)



Please cite the following paper if using the dataset:

***Tariq Al Shoura, Ali Mollaahmadi Dehaghi, Reza Razavi, Behrouz Far, and Mohammad Moshirpour. 2023. SEPE Dataset: 8K Video Sequences and Images for Analysis and Development. In Proceedings of the 14th ACM Multimedia Systems Conference (MMSys ’23), June 7–10, 2023, Vancouver, BC, Canada.***



## Table of Contents
  * [Bitrates used for each video codec and resolution combination.](#bitrates-used-for-each-video-codec-and-resolution-combination)
  * [Spatial and Temporal Perceptual Information Distribution.](#spatial-and-temporal-perceptual-information-distribution)
  * [Video Sequences Details and Encoding Evaluation.](#video-sequences-details-and-encoding-evaluation)

<table class="boarderless">
<tr><td>&#9900; <a href='#sequence-001'>Sequence 001</a></td><td>&#9900; <a href='#sequence-002'>Sequence 002</a></td><td>&#9900; <a href='#sequence-003'>Sequence 003</a></td><td>&#9900; <a href='#sequence-004'>Sequence 004</a></td></tr>
<tr><td>&#9900; <a href='#sequence-005'>Sequence 005</a></td><td>&#9900; <a href='#sequence-006'>Sequence 006</a></td><td>&#9900; <a href='#sequence-007'>Sequence 007</a></td><td>&#9900; <a href='#sequence-008'>Sequence 008</a></td></tr>
<tr><td>&#9900; <a href='#sequence-009'>Sequence 009</a></td><td>&#9900; <a href='#sequence-010'>Sequence 010</a></td><td>&#9900; <a href='#sequence-011'>Sequence 011</a></td><td>&#9900; <a href='#sequence-012'>Sequence 012</a></td></tr>
<tr><td>&#9900; <a href='#sequence-013'>Sequence 013</a></td><td>&#9900; <a href='#sequence-014'>Sequence 014</a></td><td>&#9900; <a href='#sequence-015'>Sequence 015</a></td><td>&#9900; <a href='#sequence-016'>Sequence 016</a></td></tr>
<tr><td>&#9900; <a href='#sequence-017'>Sequence 017</a></td><td>&#9900; <a href='#sequence-018'>Sequence 018</a></td><td>&#9900; <a href='#sequence-019'>Sequence 019</a></td><td>&#9900; <a href='#sequence-020'>Sequence 020</a></td></tr>
<tr><td>&#9900; <a href='#sequence-021'>Sequence 021</a></td><td>&#9900; <a href='#sequence-022'>Sequence 022</a></td><td>&#9900; <a href='#sequence-023'>Sequence 023</a></td><td>&#9900; <a href='#sequence-024'>Sequence 024</a></td></tr>
<tr><td>&#9900; <a href='#sequence-025'>Sequence 025</a></td><td>&#9900; <a href='#sequence-026'>Sequence 026</a></td><td>&#9900; <a href='#sequence-027'>Sequence 027</a></td><td>&#9900; <a href='#sequence-028'>Sequence 028</a></td></tr>
<tr><td>&#9900; <a href='#sequence-029'>Sequence 029</a></td><td>&#9900; <a href='#sequence-030'>Sequence 030</a></td><td>&#9900; <a href='#sequence-031'>Sequence 031</a></td><td>&#9900; <a href='#sequence-032'>Sequence 032</a></td></tr>
<tr><td>&#9900; <a href='#sequence-033'>Sequence 033</a></td><td>&#9900; <a href='#sequence-034'>Sequence 034</a></td><td>&#9900; <a href='#sequence-035'>Sequence 035</a></td><td>&#9900; <a href='#sequence-036'>Sequence 036</a></td></tr>
<tr><td>&#9900; <a href='#sequence-037'>Sequence 037</a></td><td>&#9900; <a href='#sequence-038'>Sequence 038</a></td><td>&#9900; <a href='#sequence-039'>Sequence 039</a></td><td>&#9900; <a href='#sequence-040'>Sequence 040</a></td></tr>
</table>


* [FFmpeg Commands](#ffmpeg-commands)
    * [Video Encoding Commands](#video-encoding-commands)
    * [Image Transforming Commands](#image-transforming-commands)
* [Video Sequences Average RBG Histogram over time](#video-sequences-average-rbg-histogram-over-time)
* [Images Histogram over time](#images-histogram-over-time)


___
## Bitrates used for each video codec and resolution combination.
*__Table  1__. Bitrates used for each video codec and resolution combination*
<table> 
    <tr>
        <td align="center" colspan="2"><b>Resolution</td>
        <td align="center"><b>Codec</td>
        <td align="center"><b>Bitrate</b><br>(Mbps)</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>8K</td>
        <td align="center" rowspan="3">8192 × 4320</td>
        <td align="center">HEVC</td>
        <td align="center">150</td>
    </tr>
    <tr>
        <td align="center">H.264<sup>1</td>
        <td align="center">150</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">65</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>4K</td>
        <td align="center" rowspan="3">4096 × 2160</td>
        <td align="center">HEVC</td>
        <td align="center">45</td>
    </tr>
    <tr>
        <td align="center">H.264</td>
        <td align="center">45</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">17.5</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>2K</td>
        <td align="center" rowspan="3">2731 × 1440</td>
        <td align="center">HEVC<sup>2</td>
        <td align="center">20</td>
    </tr>
    <tr>
        <td align="center">H.264</td>
        <td align="center">20</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">8.5</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>1K</td>
        <td align="center" rowspan="3">2048 × 1080</td>
        <td align="center">HEVC</td>
        <td align="center">10</td>
    </tr>
    <tr>
        <td align="center">H.264</td>
        <td align="center">10</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">4.5</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>720p</td>
        <td align="center" rowspan="3">1365 × 720</td>
        <td align="center">HEVC<sup>3</td>
        <td align="center">6.5</td>
    </tr>
    <tr>
        <td align="center">H.264</td>
        <td align="center">6.5</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">3</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>480p</td>
        <td align="center" rowspan="3">910 × 480</td>
        <td align="center">HEVC</td>
        <td align="center">5</td>
    </tr>
    <tr>
        <td align="center">H.264</td>
        <td align="center">5</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">2</td>
    </tr>
</table>
<sup>1</sup> <i>No Hardware acceleration support</i><br>
<sup>2</sup> <i>(2732 × 1440) for HEVC due to nvenc library constrictions</i><br>
<sup>3</sup> <i>(1366 × 720) for HEVC due to nvenc library constrictions</i>
<br><br>


[Back to Top](#idtext)

___


## Spatial and Temporal Perceptual Information Distribution.
![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/SI_TI.png)
*__Figure 1.__ Spatial and Temporal Information Distribution*

[Back to Top](#idtext)

___


## Video Sequences Details and Encoding Evaluation.
Full frame-by-frame of the evaluation metrics is available **[Here](https://github.com/talshoura/SEPE-8K-Dataset/tree/main/data_description_and_analysis/frame_by_frame_encoding_analysis)**\
The video sequences are available **[Here](https://drive.google.com/drive/folders/1EF0w8KGKXO24eG1znpgr2XJYYOzBZUGo?usp=sharing)**\
The encoded video files are available **[Here](https://drive.google.com/drive/folders/1EvDYl2AYktNyiXnseTfHFZziX5fjXQ3E?usp=sharing)**

Size of all sequences: ~472 GB\
Size of encoded videos: ~302 MB

[Back to Top](#idtext)

___

### Sequence 001
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/001_480p.png)](https://drive.google.com/drive/folders/1wX3zV3zAJcS7l59DykFUdKLYP6daCkDd?usp=sharing)\
*__Figure  2__. First Frame of Sequence 001*

Raw Sequence Size:  9.97 GB\
Source: [HERE](https://drive.google.com/drive/folders/1wX3zV3zAJcS7l59DykFUdKLYP6daCkDd?usp=sharing)

<br>

*__Table 2__. Description of encoded videos using sequence 001 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">001_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   4.97</td><td>   3.97</td><td>1</td><td>299</td><td>0</td><td>37.75</td><td>31.96</td><td>230.19</td><td>  0.861</td><td>28.87</td><td>32.09</td><td>34.91</td><td>290.40</td><td>158.81</td><td>60.76</td><td>  0.921</td><td>  0.911</td><td>  0.947</td></tr>
<tr><td align="left">001_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.46</td><td>   8.36</td><td>1</td><td>299</td><td>0</td><td>38.30</td><td>31.82</td><td>230.72</td><td>  0.852</td><td>28.84</td><td>31.87</td><td>34.76</td><td>290.77</td><td>160.34</td><td>61.02</td><td>  0.936</td><td>  0.919</td><td>  0.953</td></tr>
<tr><td align="left">001_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.01</td><td>   1.60</td><td>1</td><td>299</td><td>0</td><td>39.73</td><td>32.38</td><td>230.64</td><td>  0.851</td><td>28.96</td><td>32.81</td><td>35.36</td><td>290.98</td><td>158.97</td><td>60.94</td><td>  0.868</td><td>  0.876</td><td>  0.916</td></tr>
<tr><td align="left">001_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  24.26</td><td>  19.39</td><td>1</td><td>299</td><td>0</td><td>40.46</td><td>31.73</td><td>230.81</td><td>  0.861</td><td>28.79</td><td>31.72</td><td>34.68</td><td>290.91</td><td>160.53</td><td>60.70</td><td>  0.952</td><td>  0.930</td><td>  0.961</td></tr>
<tr><td align="left">001_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.12</td><td>   2.49</td><td>1</td><td>299</td><td>0</td><td>37.72</td><td>32.15</td><td>230.77</td><td>  0.852</td><td>28.90</td><td>32.37</td><td>35.17</td><td>290.93</td><td>160.86</td><td>60.26</td><td>  0.896</td><td>  0.896</td><td>  0.934</td></tr>
<tr><td align="left">001_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td> 106.44</td><td>  85.07</td><td>1</td><td>299</td><td>0</td><td>49.84</td><td>31.56</td><td>231.24</td><td>  0.856</td><td>28.70</td><td>31.51</td><td>34.48</td><td>291.29</td><td>161.01</td><td>61.28</td><td>  0.969</td><td>  0.948</td><td>  0.972</td></tr>
<tr><td align="left">001_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.75</td><td>  10.19</td><td>2</td><td>76</td><td>222</td><td>37.81</td><td>31.78</td><td>230.68</td><td>  0.860</td><td>28.77</td><td>31.89</td><td>34.68</td><td>291.01</td><td>159.16</td><td>60.92</td><td>  0.919</td><td>  0.905</td><td>  0.943</td></tr>
<tr><td align="left">001_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.78</td><td>  21.40</td><td>2</td><td>77</td><td>221</td><td>38.26</td><td>31.63</td><td>231.06</td><td>  0.852</td><td>28.75</td><td>31.64</td><td>34.50</td><td>291.18</td><td>160.42</td><td>61.33</td><td>  0.934</td><td>  0.912</td><td>  0.948</td></tr>
<tr><td align="left">001_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   5.62</td><td>   4.49</td><td>2</td><td>76</td><td>222</td><td>39.64</td><td>32.16</td><td>230.32</td><td>  0.850</td><td>28.82</td><td>32.54</td><td>35.12</td><td>290.86</td><td>158.09</td><td>60.40</td><td>  0.866</td><td>  0.871</td><td>  0.914</td></tr>
<tr><td align="left">001_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  60.25</td><td>  48.15</td><td>2</td><td>78</td><td>220</td><td>40.44</td><td>31.59</td><td>231.27</td><td>  0.860</td><td>28.73</td><td>31.57</td><td>34.47</td><td>291.45</td><td>160.64</td><td>61.19</td><td>  0.950</td><td>  0.925</td><td>  0.957</td></tr>
<tr><td align="left">001_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   7.99</td><td>   6.39</td><td>2</td><td>76</td><td>222</td><td>37.68</td><td>31.88</td><td>230.81</td><td>  0.851</td><td>28.79</td><td>32.01</td><td>34.83</td><td>291.13</td><td>160.03</td><td>60.50</td><td>  0.894</td><td>  0.890</td><td>  0.930</td></tr>
<tr><td align="left">001_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 199.20</td><td> 159.20</td><td>2</td><td>259</td><td>39</td><td>49.71</td><td>31.59</td><td>231.48</td><td>  0.856</td><td>28.74</td><td>31.54</td><td>34.48</td><td>291.59</td><td>161.09</td><td>61.43</td><td>  0.967</td><td>  0.947</td><td>  0.971</td></tr>
<tr><td align="left">001_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.17</td><td>  10.53</td><td>2</td><td>76</td><td>222</td><td>37.69</td><td>31.81</td><td>230.64</td><td>  0.860</td><td>28.79</td><td>31.91</td><td>34.73</td><td>290.91</td><td>159.28</td><td>60.89</td><td>  0.920</td><td>  0.906</td><td>  0.943</td></tr>
<tr><td align="left">001_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.38</td><td>  21.08</td><td>2</td><td>76</td><td>222</td><td>36.10</td><td>31.56</td><td>231.89</td><td>  0.850</td><td>28.47</td><td>31.66</td><td>34.54</td><td>292.40</td><td>160.51</td><td>61.27</td><td>  0.933</td><td>  0.913</td><td>  0.949</td></tr>
<tr><td align="left">001_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   5.73</td><td>   4.58</td><td>2</td><td>76</td><td>222</td><td>39.44</td><td>32.19</td><td>230.19</td><td>  0.851</td><td>28.84</td><td>32.57</td><td>35.17</td><td>290.63</td><td>158.22</td><td>60.42</td><td>  0.867</td><td>  0.872</td><td>  0.914</td></tr>
<tr><td align="left">001_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.80</td><td>  47.79</td><td>2</td><td>76</td><td>222</td><td>40.30</td><td>31.62</td><td>231.22</td><td>  0.860</td><td>28.73</td><td>31.60</td><td>34.52</td><td>291.38</td><td>160.66</td><td>61.14</td><td>  0.951</td><td>  0.926</td><td>  0.958</td></tr>
<tr><td align="left">001_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.46</td><td>   6.76</td><td>2</td><td>76</td><td>222</td><td>33.73</td><td>31.66</td><td>232.70</td><td>  0.848</td><td>28.13</td><td>32.01</td><td>34.84</td><td>293.85</td><td>160.25</td><td>60.55</td><td>  0.892</td><td>  0.890</td><td>  0.931</td></tr>
<tr><td align="left">001_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 199.13</td><td> 159.15</td><td>2</td><td>76</td><td>222</td><td>49.82</td><td>31.51</td><td>231.48</td><td>  0.856</td><td>28.67</td><td>31.46</td><td>34.40</td><td>291.58</td><td>161.02</td><td>61.54</td><td>  0.968</td><td>  0.947</td><td>  0.971</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 002
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/002_480p.png)](https://drive.google.com/drive/folders/1J6EYEN6rjyiHzX5Hf9_wMHrQcRB5f1j3?usp=share_link)\
*__Figure  3__. First Frame of Sequence 002*

Raw Sequence Size:  6.31 GB\
Source: [HERE](https://drive.google.com/drive/folders/1J6EYEN6rjyiHzX5Hf9_wMHrQcRB5f1j3?usp=share_link)

<br>

*__Table 3__. Description of encoded videos using sequence 002 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">002_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.57</td><td>   4.45</td><td>1</td><td>299</td><td>0</td><td>79.92</td><td>41.35</td><td>23.44</td><td>  0.976</td><td>34.88</td><td>44.03</td><td>45.14</td><td>33.33</td><td> 4.01</td><td> 3.28</td><td>  0.983</td><td>  0.992</td><td>  0.992</td></tr>
<tr><td align="left">002_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.44</td><td>   8.34</td><td>1</td><td>299</td><td>0</td><td>78.96</td><td>41.36</td><td>23.50</td><td>  0.974</td><td>34.87</td><td>44.05</td><td>45.14</td><td>33.43</td><td> 3.98</td><td> 3.30</td><td>  0.986</td><td>  0.993</td><td>  0.993</td></tr>
<tr><td align="left">002_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.41</td><td>   1.93</td><td>1</td><td>299</td><td>0</td><td>80.78</td><td>41.56</td><td>23.29</td><td>  0.974</td><td>34.93</td><td>44.19</td><td>45.55</td><td>33.17</td><td> 3.97</td><td> 3.11</td><td>  0.975</td><td>  0.988</td><td>  0.989</td></tr>
<tr><td align="left">002_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  18.18</td><td>  14.53</td><td>1</td><td>299</td><td>0</td><td>77.89</td><td>41.40</td><td>23.52</td><td>  0.976</td><td>34.86</td><td>44.08</td><td>45.25</td><td>33.48</td><td> 3.96</td><td> 3.22</td><td>  0.989</td><td>  0.994</td><td>  0.994</td></tr>
<tr><td align="left">002_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.61</td><td>   2.88</td><td>1</td><td>299</td><td>0</td><td>80.83</td><td>41.44</td><td>23.38</td><td>  0.974</td><td>34.89</td><td>44.08</td><td>45.37</td><td>33.30</td><td> 3.92</td><td> 3.16</td><td>  0.980</td><td>  0.990</td><td>  0.990</td></tr>
<tr><td align="left">002_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  77.00</td><td>  61.54</td><td>1</td><td>299</td><td>0</td><td>76.35</td><td>41.32</td><td>23.58</td><td>  0.975</td><td>34.85</td><td>44.02</td><td>45.09</td><td>33.53</td><td> 4.01</td><td> 3.32</td><td>  0.992</td><td>  0.996</td><td>  0.996</td></tr>
<tr><td align="left">002_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>   9.14</td><td>   7.30</td><td>2</td><td>76</td><td>222</td><td>79.69</td><td>40.79</td><td>23.60</td><td>  0.975</td><td>34.77</td><td>43.38</td><td>44.22</td><td>33.46</td><td> 4.26</td><td> 3.54</td><td>  0.982</td><td>  0.989</td><td>  0.989</td></tr>
<tr><td align="left">002_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  16.94</td><td>  13.54</td><td>2</td><td>76</td><td>222</td><td>78.70</td><td>40.85</td><td>23.70</td><td>  0.974</td><td>34.78</td><td>43.33</td><td>44.46</td><td>33.62</td><td> 4.26</td><td> 3.48</td><td>  0.985</td><td>  0.990</td><td>  0.991</td></tr>
<tr><td align="left">002_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   2.70</td><td>   2.15</td><td>2</td><td>76</td><td>222</td><td>79.91</td><td>40.81</td><td>23.58</td><td>  0.973</td><td>34.77</td><td>43.24</td><td>44.43</td><td>33.44</td><td> 4.28</td><td> 3.45</td><td>  0.973</td><td>  0.984</td><td>  0.985</td></tr>
<tr><td align="left">002_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  41.10</td><td>  32.84</td><td>2</td><td>76</td><td>222</td><td>77.89</td><td>40.95</td><td>23.63</td><td>  0.976</td><td>34.79</td><td>43.42</td><td>44.64</td><td>33.54</td><td> 4.23</td><td> 3.40</td><td>  0.988</td><td>  0.992</td><td>  0.992</td></tr>
<tr><td align="left">002_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   4.71</td><td>   3.76</td><td>2</td><td>76</td><td>222</td><td>80.29</td><td>40.81</td><td>23.58</td><td>  0.973</td><td>34.76</td><td>43.35</td><td>44.33</td><td>33.44</td><td> 4.21</td><td> 3.51</td><td>  0.978</td><td>  0.987</td><td>  0.988</td></tr>
<tr><td align="left">002_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 194.86</td><td> 155.73</td><td>2</td><td>75</td><td>223</td><td>76.23</td><td>41.21</td><td>23.65</td><td>  0.975</td><td>34.85</td><td>43.87</td><td>44.89</td><td>33.61</td><td> 4.08</td><td> 3.39</td><td>  0.992</td><td>  0.995</td><td>  0.995</td></tr>
<tr><td align="left">002_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>   8.13</td><td>   6.50</td><td>2</td><td>76</td><td>222</td><td>79.42</td><td>40.95</td><td>23.57</td><td>  0.975</td><td>34.79</td><td>43.58</td><td>44.48</td><td>33.45</td><td> 4.17</td><td> 3.45</td><td>  0.982</td><td>  0.990</td><td>  0.990</td></tr>
<tr><td align="left">002_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  13.73</td><td>  10.97</td><td>2</td><td>76</td><td>222</td><td>76.44</td><td>40.93</td><td>23.95</td><td>  0.973</td><td>34.59</td><td>43.54</td><td>44.67</td><td>34.03</td><td> 4.17</td><td> 3.42</td><td>  0.984</td><td>  0.991</td><td>  0.991</td></tr>
<tr><td align="left">002_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   2.39</td><td>   1.91</td><td>2</td><td>76</td><td>222</td><td>79.74</td><td>40.84</td><td>23.60</td><td>  0.973</td><td>34.78</td><td>43.26</td><td>44.48</td><td>33.47</td><td> 4.26</td><td> 3.44</td><td>  0.974</td><td>  0.985</td><td>  0.986</td></tr>
<tr><td align="left">002_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  30.40</td><td>  24.30</td><td>2</td><td>76</td><td>222</td><td>77.68</td><td>41.11</td><td>23.60</td><td>  0.976</td><td>34.81</td><td>43.63</td><td>44.89</td><td>33.53</td><td> 4.14</td><td> 3.33</td><td>  0.988</td><td>  0.993</td><td>  0.993</td></tr>
<tr><td align="left">002_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   4.15</td><td>   3.32</td><td>2</td><td>76</td><td>222</td><td>73.98</td><td>40.67</td><td>24.54</td><td>  0.971</td><td>34.22</td><td>43.46</td><td>44.33</td><td>34.89</td><td> 4.17</td><td> 3.52</td><td>  0.975</td><td>  0.987</td><td>  0.988</td></tr>
<tr><td align="left">002_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 125.21</td><td> 100.07</td><td>2</td><td>76</td><td>222</td><td>76.23</td><td>41.15</td><td>23.64</td><td>  0.975</td><td>34.82</td><td>43.81</td><td>44.83</td><td>33.60</td><td> 4.09</td><td> 3.37</td><td>  0.992</td><td>  0.995</td><td>  0.995</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 003
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/003_480p.png)](https://drive.google.com/drive/folders/1veJuOduzKV0UUrrx_Rk2zRwDhOp7UOHn?usp=share_link)\
*__Figure  4__. First Frame of Sequence 003*

Raw Sequence Size:  7.56 GB\
Source: [HERE](https://drive.google.com/drive/folders/1veJuOduzKV0UUrrx_Rk2zRwDhOp7UOHn?usp=share_link)

<br>

*__Table 4__. Description of encoded videos using sequence 003 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">003_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.53</td><td>   4.42</td><td>1</td><td>299</td><td>0</td><td>11.93</td><td>35.13</td><td>474.33</td><td>  0.694</td><td>20.17</td><td>43.52</td><td>41.69</td><td>709.55</td><td> 3.11</td><td> 4.67</td><td>  0.706</td><td>  0.977</td><td>  0.974</td></tr>
<tr><td align="left">003_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.50</td><td>   8.39</td><td>1</td><td>299</td><td>0</td><td> 9.39</td><td>35.10</td><td>475.78</td><td>  0.700</td><td>20.18</td><td>43.64</td><td>41.47</td><td>711.77</td><td> 3.01</td><td> 4.93</td><td>  0.733</td><td>  0.980</td><td>  0.976</td></tr>
<tr><td align="left">003_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.47</td><td>   1.97</td><td>1</td><td>299</td><td>0</td><td>18.86</td><td>35.30</td><td>460.28</td><td>  0.695</td><td>20.29</td><td>44.07</td><td>41.54</td><td>688.52</td><td> 2.73</td><td> 4.85</td><td>  0.673</td><td>  0.975</td><td>  0.967</td></tr>
<tr><td align="left">003_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  19.20</td><td>  15.35</td><td>1</td><td>299</td><td>0</td><td> 6.55</td><td>35.00</td><td>476.06</td><td>  0.696</td><td>20.19</td><td>43.42</td><td>41.40</td><td>712.05</td><td> 3.19</td><td> 5.01</td><td>  0.778</td><td>  0.984</td><td>  0.980</td></tr>
<tr><td align="left">003_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.71</td><td>   2.96</td><td>1</td><td>299</td><td>0</td><td>15.35</td><td>35.12</td><td>471.23</td><td>  0.697</td><td>20.19</td><td>43.79</td><td>41.38</td><td>705.04</td><td> 2.91</td><td> 5.03</td><td>  0.681</td><td>  0.976</td><td>  0.970</td></tr>
<tr><td align="left">003_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  74.66</td><td>  59.67</td><td>1</td><td>299</td><td>0</td><td> 4.06</td><td>35.04</td><td>476.63</td><td>  0.699</td><td>20.20</td><td>43.54</td><td>41.38</td><td>712.91</td><td> 3.10</td><td> 5.05</td><td>  0.858</td><td>  0.990</td><td>  0.988</td></tr>
<tr><td align="left">003_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.17</td><td>   9.73</td><td>2</td><td>76</td><td>222</td><td>11.79</td><td>35.02</td><td>474.23</td><td>  0.694</td><td>20.15</td><td>43.46</td><td>41.44</td><td>709.34</td><td> 3.09</td><td> 4.91</td><td>  0.705</td><td>  0.978</td><td>  0.974</td></tr>
<tr><td align="left">003_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  23.98</td><td>  19.16</td><td>2</td><td>76</td><td>222</td><td> 9.32</td><td>34.95</td><td>475.77</td><td>  0.700</td><td>20.16</td><td>43.46</td><td>41.24</td><td>711.67</td><td> 3.10</td><td> 5.15</td><td>  0.732</td><td>  0.980</td><td>  0.975</td></tr>
<tr><td align="left">003_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   5.77</td><td>   4.61</td><td>2</td><td>76</td><td>222</td><td>18.69</td><td>35.29</td><td>460.65</td><td>  0.695</td><td>20.28</td><td>44.00</td><td>41.58</td><td>689.10</td><td> 2.73</td><td> 4.76</td><td>  0.673</td><td>  0.976</td><td>  0.968</td></tr>
<tr><td align="left">003_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  53.49</td><td>  42.75</td><td>2</td><td>76</td><td>222</td><td> 6.54</td><td>34.85</td><td>476.74</td><td>  0.696</td><td>20.17</td><td>43.18</td><td>41.20</td><td>712.98</td><td> 3.32</td><td> 5.21</td><td>  0.777</td><td>  0.983</td><td>  0.978</td></tr>
<tr><td align="left">003_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.19</td><td>   6.55</td><td>2</td><td>76</td><td>222</td><td>15.15</td><td>35.11</td><td>470.33</td><td>  0.697</td><td>20.19</td><td>43.72</td><td>41.42</td><td>703.70</td><td> 2.91</td><td> 4.95</td><td>  0.680</td><td>  0.976</td><td>  0.970</td></tr>
<tr><td align="left">003_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 190.72</td><td> 152.42</td><td>2</td><td>76</td><td>222</td><td> 4.05</td><td>34.97</td><td>477.01</td><td>  0.698</td><td>20.23</td><td>43.40</td><td>41.27</td><td>713.40</td><td> 3.22</td><td> 5.21</td><td>  0.857</td><td>  0.989</td><td>  0.986</td></tr>
<tr><td align="left">003_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.66</td><td>  10.12</td><td>2</td><td>76</td><td>222</td><td>11.81</td><td>35.03</td><td>474.23</td><td>  0.695</td><td>20.17</td><td>43.51</td><td>41.41</td><td>709.34</td><td> 3.08</td><td> 4.95</td><td>  0.707</td><td>  0.977</td><td>  0.973</td></tr>
<tr><td align="left">003_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  25.58</td><td>  20.44</td><td>2</td><td>76</td><td>222</td><td> 8.07</td><td>34.90</td><td>478.07</td><td>  0.696</td><td>20.03</td><td>43.46</td><td>41.22</td><td>715.03</td><td> 3.11</td><td> 5.18</td><td>  0.728</td><td>  0.979</td><td>  0.974</td></tr>
<tr><td align="left">003_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   5.73</td><td>   4.58</td><td>2</td><td>76</td><td>222</td><td>18.71</td><td>35.25</td><td>461.05</td><td>  0.695</td><td>20.29</td><td>43.96</td><td>41.52</td><td>689.67</td><td> 2.77</td><td> 4.83</td><td>  0.673</td><td>  0.975</td><td>  0.968</td></tr>
<tr><td align="left">003_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.22</td><td>  46.53</td><td>2</td><td>76</td><td>222</td><td> 6.52</td><td>34.89</td><td>476.50</td><td>  0.696</td><td>20.17</td><td>43.28</td><td>41.22</td><td>712.64</td><td> 3.25</td><td> 5.19</td><td>  0.778</td><td>  0.983</td><td>  0.979</td></tr>
<tr><td align="left">003_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.24</td><td>   6.58</td><td>2</td><td>76</td><td>222</td><td>13.12</td><td>35.04</td><td>475.87</td><td>  0.689</td><td>19.98</td><td>43.78</td><td>41.36</td><td>711.83</td><td> 2.89</td><td> 5.03</td><td>  0.668</td><td>  0.976</td><td>  0.970</td></tr>
<tr><td align="left">003_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 200.12</td><td> 159.93</td><td>2</td><td>76</td><td>222</td><td> 4.05</td><td>34.90</td><td>476.97</td><td>  0.698</td><td>20.19</td><td>43.39</td><td>41.13</td><td>713.32</td><td> 3.19</td><td> 5.32</td><td>  0.857</td><td>  0.989</td><td>  0.986</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 004
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/004_480p.png)](https://drive.google.com/drive/folders/1qP8jLVDdv1xSiWFZk7WiMmilzpxBWZxR?usp=sharing)\
*__Figure  5__. First Frame of Sequence 004*

Raw Sequence Size:  6.27 GB\
Source: [HERE](https://drive.google.com/drive/folders/1qP8jLVDdv1xSiWFZk7WiMmilzpxBWZxR?usp=sharing)

<br>

*__Table 5__. Description of encoded videos using sequence 004 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">004_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.53</td><td>   4.42</td><td>1</td><td>299</td><td>0</td><td>72.83</td><td>36.29</td><td>215.01</td><td>  0.920</td><td>24.82</td><td>41.19</td><td>42.85</td><td>319.92</td><td> 6.15</td><td> 4.21</td><td>  0.953</td><td>  0.989</td><td>  0.993</td></tr>
<tr><td align="left">004_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.48</td><td>   8.38</td><td>1</td><td>299</td><td>0</td><td>74.26</td><td>36.44</td><td>215.12</td><td>  0.914</td><td>24.83</td><td>41.30</td><td>43.20</td><td>320.25</td><td> 5.99</td><td> 3.85</td><td>  0.961</td><td>  0.990</td><td>  0.994</td></tr>
<tr><td align="left">004_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.43</td><td>   1.94</td><td>1</td><td>299</td><td>0</td><td>67.88</td><td>36.28</td><td>215.12</td><td>  0.914</td><td>24.83</td><td>41.19</td><td>42.81</td><td>320.04</td><td> 6.30</td><td> 4.25</td><td>  0.925</td><td>  0.982</td><td>  0.987</td></tr>
<tr><td align="left">004_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  19.21</td><td>  15.35</td><td>1</td><td>299</td><td>0</td><td>75.87</td><td>36.39</td><td>215.15</td><td>  0.920</td><td>24.82</td><td>41.20</td><td>43.14</td><td>320.22</td><td> 6.14</td><td> 3.89</td><td>  0.969</td><td>  0.992</td><td>  0.995</td></tr>
<tr><td align="left">004_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.69</td><td>   2.95</td><td>1</td><td>299</td><td>0</td><td>70.61</td><td>36.57</td><td>215.14</td><td>  0.914</td><td>24.82</td><td>41.48</td><td>43.40</td><td>320.42</td><td> 5.77</td><td> 3.67</td><td>  0.941</td><td>  0.986</td><td>  0.991</td></tr>
<tr><td align="left">004_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  75.61</td><td>  60.43</td><td>1</td><td>299</td><td>0</td><td>77.49</td><td>36.39</td><td>215.34</td><td>  0.917</td><td>24.82</td><td>41.22</td><td>43.12</td><td>320.51</td><td> 6.06</td><td> 3.94</td><td>  0.978</td><td>  0.994</td><td>  0.997</td></tr>
<tr><td align="left">004_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  10.95</td><td>   8.75</td><td>2</td><td>76</td><td>222</td><td>72.64</td><td>36.02</td><td>215.37</td><td>  0.919</td><td>24.77</td><td>40.89</td><td>42.42</td><td>320.39</td><td> 6.35</td><td> 4.34</td><td>  0.952</td><td>  0.986</td><td>  0.991</td></tr>
<tr><td align="left">004_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  20.97</td><td>  16.76</td><td>2</td><td>76</td><td>222</td><td>74.15</td><td>36.22</td><td>215.23</td><td>  0.914</td><td>24.78</td><td>40.96</td><td>42.93</td><td>320.33</td><td> 6.29</td><td> 3.97</td><td>  0.960</td><td>  0.988</td><td>  0.993</td></tr>
<tr><td align="left">004_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   3.41</td><td>   2.73</td><td>2</td><td>76</td><td>222</td><td>67.63</td><td>36.05</td><td>215.07</td><td>  0.913</td><td>24.77</td><td>40.87</td><td>42.51</td><td>319.93</td><td> 6.41</td><td> 4.28</td><td>  0.924</td><td>  0.980</td><td>  0.985</td></tr>
<tr><td align="left">004_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  46.38</td><td>  37.06</td><td>2</td><td>76</td><td>222</td><td>75.87</td><td>36.19</td><td>215.43</td><td>  0.920</td><td>24.78</td><td>40.97</td><td>42.84</td><td>320.56</td><td> 6.33</td><td> 4.03</td><td>  0.968</td><td>  0.989</td><td>  0.994</td></tr>
<tr><td align="left">004_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   6.44</td><td>   5.15</td><td>2</td><td>76</td><td>222</td><td>70.42</td><td>36.23</td><td>215.32</td><td>  0.914</td><td>24.76</td><td>40.99</td><td>42.93</td><td>320.52</td><td> 6.20</td><td> 3.91</td><td>  0.939</td><td>  0.984</td><td>  0.989</td></tr>
<tr><td align="left">004_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 190.99</td><td> 152.64</td><td>2</td><td>78</td><td>220</td><td>77.30</td><td>36.35</td><td>215.43</td><td>  0.917</td><td>24.84</td><td>41.16</td><td>43.06</td><td>320.61</td><td> 6.17</td><td> 3.99</td><td>  0.978</td><td>  0.993</td><td>  0.996</td></tr>
<tr><td align="left">004_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  11.99</td><td>   9.58</td><td>2</td><td>76</td><td>222</td><td>72.56</td><td>36.09</td><td>215.34</td><td>  0.919</td><td>24.77</td><td>40.96</td><td>42.53</td><td>320.38</td><td> 6.28</td><td> 4.26</td><td>  0.953</td><td>  0.987</td><td>  0.992</td></tr>
<tr><td align="left">004_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  23.21</td><td>  18.55</td><td>2</td><td>76</td><td>222</td><td>69.26</td><td>36.20</td><td>216.38</td><td>  0.914</td><td>24.58</td><td>41.03</td><td>42.99</td><td>322.03</td><td> 6.21</td><td> 3.93</td><td>  0.959</td><td>  0.988</td><td>  0.993</td></tr>
<tr><td align="left">004_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   3.26</td><td>   2.61</td><td>2</td><td>76</td><td>222</td><td>67.59</td><td>36.09</td><td>215.03</td><td>  0.913</td><td>24.77</td><td>40.92</td><td>42.57</td><td>319.90</td><td> 6.36</td><td> 4.23</td><td>  0.924</td><td>  0.980</td><td>  0.986</td></tr>
<tr><td align="left">004_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  48.00</td><td>  38.36</td><td>2</td><td>76</td><td>222</td><td>75.79</td><td>36.25</td><td>215.41</td><td>  0.920</td><td>24.78</td><td>41.04</td><td>42.93</td><td>320.55</td><td> 6.26</td><td> 3.98</td><td>  0.969</td><td>  0.990</td><td>  0.994</td></tr>
<tr><td align="left">004_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   5.94</td><td>   4.75</td><td>2</td><td>76</td><td>222</td><td>62.89</td><td>36.14</td><td>218.72</td><td>  0.911</td><td>24.37</td><td>41.03</td><td>43.00</td><td>325.56</td><td> 6.16</td><td> 3.87</td><td>  0.935</td><td>  0.984</td><td>  0.990</td></tr>
<tr><td align="left">004_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 164.67</td><td> 131.61</td><td>2</td><td>76</td><td>222</td><td>77.46</td><td>36.27</td><td>215.45</td><td>  0.917</td><td>24.80</td><td>41.06</td><td>42.96</td><td>320.63</td><td> 6.22</td><td> 3.98</td><td>  0.978</td><td>  0.993</td><td>  0.996</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 005
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/005_480p.png)](https://drive.google.com/drive/folders/10ArGk3Synyx9gXd2CHl6VXt9EFD7zQtC?usp=sharing)\
*__Figure  6__. First Frame of Sequence 005*

Raw Sequence Size: 17.17 GB\
Source: [HERE](https://drive.google.com/drive/folders/10ArGk3Synyx9gXd2CHl6VXt9EFD7zQtC?usp=sharing)

<br>

*__Table 6__. Description of encoded videos using sequence 005 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">005_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   6.03</td><td>   4.82</td><td>1</td><td>299</td><td>0</td><td>12.43</td><td>33.88</td><td>131.55</td><td>  0.695</td><td>25.77</td><td>36.49</td><td>39.37</td><td>191.28</td><td>16.06</td><td> 8.12</td><td>  0.635</td><td>  0.902</td><td>  0.938</td></tr>
<tr><td align="left">005_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  11.59</td><td>   9.26</td><td>1</td><td>299</td><td>0</td><td>10.04</td><td>33.43</td><td>135.89</td><td>  0.706</td><td>25.64</td><td>36.02</td><td>38.63</td><td>197.03</td><td>17.76</td><td> 9.55</td><td>  0.648</td><td>  0.897</td><td>  0.928</td></tr>
<tr><td align="left">005_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.73</td><td>   2.18</td><td>1</td><td>299</td><td>0</td><td>24.77</td><td>35.34</td><td>109.96</td><td>  0.705</td><td>26.65</td><td>38.22</td><td>41.14</td><td>160.72</td><td>11.24</td><td> 5.67</td><td>  0.646</td><td>  0.922</td><td>  0.958</td></tr>
<tr><td align="left">005_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  23.94</td><td>  19.13</td><td>1</td><td>299</td><td>0</td><td> 7.88</td><td>33.06</td><td>139.23</td><td>  0.693</td><td>25.55</td><td>35.68</td><td>37.95</td><td>201.32</td><td>19.06</td><td>11.03</td><td>  0.681</td><td>  0.897</td><td>  0.918</td></tr>
<tr><td align="left">005_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   4.06</td><td>   3.25</td><td>1</td><td>299</td><td>0</td><td>17.11</td><td>34.57</td><td>122.95</td><td>  0.706</td><td>26.09</td><td>37.33</td><td>40.28</td><td>179.42</td><td>13.45</td><td> 6.73</td><td>  0.630</td><td>  0.912</td><td>  0.950</td></tr>
<tr><td align="left">005_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  92.75</td><td>  74.13</td><td>1</td><td>299</td><td>0</td><td> 5.84</td><td>32.63</td><td>141.49</td><td>  0.699</td><td>25.51</td><td>35.26</td><td>37.13</td><td>203.73</td><td>20.83</td><td>13.17</td><td>  0.764</td><td>  0.909</td><td>  0.912</td></tr>
<tr><td align="left">005_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.90</td><td>  11.11</td><td>2</td><td>76</td><td>222</td><td>12.20</td><td>34.02</td><td>130.79</td><td>  0.694</td><td>25.79</td><td>36.72</td><td>39.56</td><td>190.51</td><td>15.01</td><td> 7.70</td><td>  0.635</td><td>  0.908</td><td>  0.943</td></tr>
<tr><td align="left">005_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  27.95</td><td>  22.34</td><td>2</td><td>76</td><td>222</td><td> 9.95</td><td>33.63</td><td>135.70</td><td>  0.706</td><td>25.65</td><td>36.36</td><td>38.89</td><td>197.25</td><td>16.37</td><td> 8.94</td><td>  0.646</td><td>  0.904</td><td>  0.934</td></tr>
<tr><td align="left">005_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   7.25</td><td>   5.79</td><td>2</td><td>76</td><td>222</td><td>24.49</td><td>35.27</td><td>110.48</td><td>  0.701</td><td>26.65</td><td>38.10</td><td>41.05</td><td>161.46</td><td>11.34</td><td> 5.69</td><td>  0.640</td><td>  0.920</td><td>  0.956</td></tr>
<tr><td align="left">005_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  62.56</td><td>  50.00</td><td>2</td><td>76</td><td>222</td><td> 7.82</td><td>33.15</td><td>139.34</td><td>  0.693</td><td>25.55</td><td>35.79</td><td>38.09</td><td>201.73</td><td>18.50</td><td>10.63</td><td>  0.679</td><td>  0.900</td><td>  0.921</td></tr>
<tr><td align="left">005_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   9.30</td><td>   7.44</td><td>2</td><td>76</td><td>222</td><td>16.85</td><td>34.72</td><td>122.58</td><td>  0.705</td><td>26.11</td><td>37.59</td><td>40.45</td><td>179.18</td><td>12.52</td><td> 6.40</td><td>  0.627</td><td>  0.917</td><td>  0.952</td></tr>
<tr><td align="left">005_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 210.06</td><td> 167.88</td><td>2</td><td>76</td><td>222</td><td> 5.76</td><td>32.78</td><td>141.30</td><td>  0.699</td><td>25.61</td><td>35.39</td><td>37.33</td><td>203.58</td><td>20.62</td><td>12.87</td><td>  0.760</td><td>  0.909</td><td>  0.913</td></tr>
<tr><td align="left">005_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.19</td><td>  10.54</td><td>2</td><td>76</td><td>222</td><td>12.28</td><td>33.90</td><td>131.28</td><td>  0.694</td><td>25.80</td><td>36.51</td><td>39.38</td><td>190.92</td><td>15.90</td><td> 8.06</td><td>  0.632</td><td>  0.902</td><td>  0.939</td></tr>
<tr><td align="left">005_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.31</td><td>  21.03</td><td>2</td><td>76</td><td>222</td><td>10.14</td><td>33.49</td><td>134.44</td><td>  0.710</td><td>25.63</td><td>36.15</td><td>38.70</td><td>194.99</td><td>17.28</td><td> 9.36</td><td>  0.646</td><td>  0.898</td><td>  0.929</td></tr>
<tr><td align="left">005_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   7.00</td><td>   5.60</td><td>2</td><td>76</td><td>222</td><td>24.52</td><td>35.24</td><td>110.59</td><td>  0.702</td><td>26.65</td><td>38.03</td><td>41.04</td><td>161.54</td><td>11.60</td><td> 5.76</td><td>  0.640</td><td>  0.919</td><td>  0.956</td></tr>
<tr><td align="left">005_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.11</td><td>  47.24</td><td>2</td><td>76</td><td>222</td><td> 7.84</td><td>33.03</td><td>139.30</td><td>  0.693</td><td>25.58</td><td>35.64</td><td>37.88</td><td>201.33</td><td>19.26</td><td>11.19</td><td>  0.678</td><td>  0.895</td><td>  0.915</td></tr>
<tr><td align="left">005_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   9.05</td><td>   7.23</td><td>2</td><td>76</td><td>222</td><td>17.75</td><td>34.61</td><td>120.42</td><td>  0.713</td><td>26.08</td><td>37.44</td><td>40.31</td><td>175.68</td><td>13.12</td><td> 6.66</td><td>  0.633</td><td>  0.913</td><td>  0.950</td></tr>
<tr><td align="left">005_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 197.01</td><td> 157.45</td><td>2</td><td>76</td><td>222</td><td> 5.84</td><td>32.57</td><td>141.66</td><td>  0.699</td><td>25.54</td><td>35.19</td><td>36.99</td><td>203.78</td><td>21.21</td><td>13.64</td><td>  0.761</td><td>  0.905</td><td>  0.906</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 006
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/006_480p.png)](https://drive.google.com/drive/folders/1hkZd8n7F7iTMkahTHW2aZyTZiRaXktDi?usp=share_link)\
*__Figure  7__. First Frame of Sequence 006*

Raw Sequence Size: 16.86 GB\
Source: [HERE](https://drive.google.com/drive/folders/1hkZd8n7F7iTMkahTHW2aZyTZiRaXktDi?usp=share_link)

<br>

*__Table 7__. Description of encoded videos using sequence 006 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">006_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.03</td><td>   4.02</td><td>1</td><td>299</td><td>0</td><td> 5.25</td><td>35.06</td><td>229.88</td><td>  0.920</td><td>23.78</td><td>36.05</td><td>45.34</td><td>339.64</td><td>18.78</td><td> 1.97</td><td>  0.939</td><td>  0.975</td><td>  0.986</td></tr>
<tr><td align="left">006_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.43</td><td>   8.33</td><td>1</td><td>299</td><td>0</td><td> 7.70</td><td>34.73</td><td>230.79</td><td>  0.917</td><td>23.75</td><td>35.90</td><td>44.54</td><td>340.81</td><td>19.28</td><td> 2.35</td><td>  0.940</td><td>  0.974</td><td>  0.981</td></tr>
<tr><td align="left">006_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.40</td><td>   1.92</td><td>1</td><td>299</td><td>0</td><td> 3.70</td><td>35.55</td><td>229.44</td><td>  0.916</td><td>23.82</td><td>36.14</td><td>46.67</td><td>339.11</td><td>18.68</td><td> 1.50</td><td>  0.924</td><td>  0.965</td><td>  0.991</td></tr>
<tr><td align="left">006_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  20.18</td><td>  16.13</td><td>1</td><td>299</td><td>0</td><td>11.29</td><td>34.41</td><td>231.05</td><td>  0.920</td><td>23.72</td><td>35.88</td><td>43.63</td><td>341.06</td><td>19.16</td><td> 2.88</td><td>  0.939</td><td>  0.972</td><td>  0.973</td></tr>
<tr><td align="left">006_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.01</td><td>   2.41</td><td>1</td><td>299</td><td>0</td><td> 3.50</td><td>35.25</td><td>230.11</td><td>  0.916</td><td>23.80</td><td>36.20</td><td>45.76</td><td>340.23</td><td>18.22</td><td> 1.84</td><td>  0.933</td><td>  0.971</td><td>  0.989</td></tr>
<tr><td align="left">006_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  68.53</td><td>  54.77</td><td>1</td><td>299</td><td>0</td><td>29.24</td><td>33.87</td><td>232.39</td><td>  0.918</td><td>23.67</td><td>35.55</td><td>42.38</td><td>342.54</td><td>20.36</td><td> 3.80</td><td>  0.927</td><td>  0.965</td><td>  0.962</td></tr>
<tr><td align="left">006_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.99</td><td>  10.38</td><td>2</td><td>294</td><td>4</td><td> 5.26</td><td>34.76</td><td>230.09</td><td>  0.920</td><td>23.78</td><td>35.97</td><td>44.55</td><td>339.78</td><td>19.06</td><td> 2.36</td><td>  0.938</td><td>  0.974</td><td>  0.983</td></tr>
<tr><td align="left">006_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.54</td><td>  21.21</td><td>2</td><td>298</td><td>0</td><td> 7.71</td><td>34.51</td><td>230.84</td><td>  0.917</td><td>23.75</td><td>35.83</td><td>43.96</td><td>340.75</td><td>19.53</td><td> 2.67</td><td>  0.939</td><td>  0.972</td><td>  0.977</td></tr>
<tr><td align="left">006_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   4.93</td><td>   3.94</td><td>2</td><td>167</td><td>131</td><td> 3.69</td><td>35.30</td><td>229.46</td><td>  0.916</td><td>23.82</td><td>36.15</td><td>45.93</td><td>339.11</td><td>18.59</td><td> 1.75</td><td>  0.924</td><td>  0.965</td><td>  0.989</td></tr>
<tr><td align="left">006_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  59.45</td><td>  47.51</td><td>2</td><td>298</td><td>0</td><td>11.31</td><td>34.16</td><td>231.14</td><td>  0.920</td><td>23.73</td><td>35.72</td><td>43.02</td><td>340.95</td><td>19.73</td><td> 3.30</td><td>  0.937</td><td>  0.968</td><td>  0.967</td></tr>
<tr><td align="left">006_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.08</td><td>   6.45</td><td>2</td><td>233</td><td>65</td><td> 3.46</td><td>35.15</td><td>229.95</td><td>  0.916</td><td>23.80</td><td>36.14</td><td>45.51</td><td>339.91</td><td>18.44</td><td> 1.92</td><td>  0.932</td><td>  0.970</td><td>  0.987</td></tr>
<tr><td align="left">006_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 222.55</td><td> 177.86</td><td>2</td><td>298</td><td>0</td><td>30.14</td><td>33.76</td><td>232.88</td><td>  0.918</td><td>23.78</td><td>35.57</td><td>41.94</td><td>343.06</td><td>20.71</td><td> 4.32</td><td>  0.919</td><td>  0.960</td><td>  0.956</td></tr>
<tr><td align="left">006_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.13</td><td>  10.49</td><td>2</td><td>76</td><td>222</td><td> 5.25</td><td>34.85</td><td>229.98</td><td>  0.920</td><td>23.79</td><td>35.99</td><td>44.78</td><td>339.68</td><td>18.96</td><td> 2.23</td><td>  0.938</td><td>  0.974</td><td>  0.983</td></tr>
<tr><td align="left">006_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.50</td><td>  21.18</td><td>2</td><td>76</td><td>222</td><td> 7.50</td><td>34.59</td><td>230.74</td><td>  0.917</td><td>23.74</td><td>35.88</td><td>44.16</td><td>340.64</td><td>19.32</td><td> 2.56</td><td>  0.939</td><td>  0.973</td><td>  0.978</td></tr>
<tr><td align="left">006_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   3.72</td><td>   2.97</td><td>2</td><td>76</td><td>222</td><td> 3.68</td><td>35.33</td><td>229.40</td><td>  0.916</td><td>23.82</td><td>36.18</td><td>45.99</td><td>339.04</td><td>18.52</td><td> 1.73</td><td>  0.924</td><td>  0.965</td><td>  0.990</td></tr>
<tr><td align="left">006_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.15</td><td>  47.27</td><td>2</td><td>76</td><td>222</td><td>11.33</td><td>34.24</td><td>231.13</td><td>  0.920</td><td>23.73</td><td>35.76</td><td>43.22</td><td>341.01</td><td>19.59</td><td> 3.15</td><td>  0.936</td><td>  0.970</td><td>  0.969</td></tr>
<tr><td align="left">006_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.17</td><td>   5.73</td><td>2</td><td>76</td><td>222</td><td> 3.21</td><td>35.15</td><td>229.87</td><td>  0.916</td><td>23.75</td><td>36.15</td><td>45.54</td><td>339.72</td><td>18.43</td><td> 1.92</td><td>  0.932</td><td>  0.970</td><td>  0.988</td></tr>
<tr><td align="left">006_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 198.74</td><td> 158.84</td><td>2</td><td>76</td><td>222</td><td>30.17</td><td>33.70</td><td>232.78</td><td>  0.918</td><td>23.68</td><td>35.48</td><td>41.94</td><td>342.95</td><td>20.68</td><td> 4.21</td><td>  0.921</td><td>  0.963</td><td>  0.957</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 007
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/007_480p.png)](https://drive.google.com/drive/folders/1-crbTwtjwLnkPu5OW4gL6em0o3_Tn3pp?usp=share_link)\
*__Figure  8__. First Frame of Sequence 007*

Raw Sequence Size:  7.99 GB\
Source: [HERE](https://drive.google.com/drive/folders/1-crbTwtjwLnkPu5OW4gL6em0o3_Tn3pp?usp=share_link)

<br>

*__Table 8__. Description of encoded videos using sequence 007 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">007_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.41</td><td>   4.32</td><td>1</td><td>299</td><td>0</td><td> 8.66</td><td>34.28</td><td>213.60</td><td>  0.777</td><td>24.47</td><td>37.39</td><td>40.98</td><td>314.98</td><td>15.21</td><td> 6.44</td><td>  0.803</td><td>  0.940</td><td>  0.967</td></tr>
<tr><td align="left">007_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.15</td><td>   8.12</td><td>1</td><td>299</td><td>0</td><td> 7.69</td><td>34.13</td><td>215.72</td><td>  0.771</td><td>24.42</td><td>37.15</td><td>40.83</td><td>317.99</td><td>15.94</td><td> 6.59</td><td>  0.822</td><td>  0.944</td><td>  0.970</td></tr>
<tr><td align="left">007_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.42</td><td>   1.94</td><td>1</td><td>299</td><td>0</td><td>13.84</td><td>34.73</td><td>204.59</td><td>  0.770</td><td>24.77</td><td>37.91</td><td>41.50</td><td>301.86</td><td>14.13</td><td> 5.94</td><td>  0.768</td><td>  0.929</td><td>  0.959</td></tr>
<tr><td align="left">007_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  20.86</td><td>  16.67</td><td>1</td><td>299</td><td>0</td><td> 6.96</td><td>34.12</td><td>216.91</td><td>  0.777</td><td>24.39</td><td>37.12</td><td>40.87</td><td>319.76</td><td>15.95</td><td> 6.48</td><td>  0.849</td><td>  0.952</td><td>  0.976</td></tr>
<tr><td align="left">007_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.65</td><td>   2.92</td><td>1</td><td>299</td><td>0</td><td>10.81</td><td>34.52</td><td>209.93</td><td>  0.771</td><td>24.59</td><td>37.61</td><td>41.36</td><td>309.81</td><td>14.70</td><td> 5.92</td><td>  0.780</td><td>  0.935</td><td>  0.963</td></tr>
<tr><td align="left">007_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  85.78</td><td>  68.56</td><td>1</td><td>299</td><td>0</td><td> 7.94</td><td>33.99</td><td>218.02</td><td>  0.774</td><td>24.36</td><td>36.96</td><td>40.65</td><td>321.22</td><td>16.45</td><td> 6.79</td><td>  0.894</td><td>  0.966</td><td>  0.984</td></tr>
<tr><td align="left">007_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.97</td><td>  10.36</td><td>2</td><td>76</td><td>222</td><td> 8.63</td><td>34.12</td><td>214.21</td><td>  0.776</td><td>24.45</td><td>37.28</td><td>40.64</td><td>315.79</td><td>15.32</td><td> 6.75</td><td>  0.800</td><td>  0.938</td><td>  0.966</td></tr>
<tr><td align="left">007_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.79</td><td>  21.41</td><td>2</td><td>76</td><td>222</td><td> 7.66</td><td>34.06</td><td>215.99</td><td>  0.771</td><td>24.40</td><td>37.10</td><td>40.68</td><td>318.37</td><td>15.95</td><td> 6.70</td><td>  0.819</td><td>  0.941</td><td>  0.969</td></tr>
<tr><td align="left">007_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   5.28</td><td>   4.22</td><td>2</td><td>76</td><td>222</td><td>13.75</td><td>34.66</td><td>204.32</td><td>  0.770</td><td>24.76</td><td>37.86</td><td>41.36</td><td>301.51</td><td>13.98</td><td> 5.93</td><td>  0.766</td><td>  0.928</td><td>  0.959</td></tr>
<tr><td align="left">007_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  60.31</td><td>  48.20</td><td>2</td><td>76</td><td>222</td><td> 6.94</td><td>33.97</td><td>217.61</td><td>  0.776</td><td>24.36</td><td>37.00</td><td>40.56</td><td>320.66</td><td>16.21</td><td> 6.84</td><td>  0.847</td><td>  0.949</td><td>  0.974</td></tr>
<tr><td align="left">007_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.04</td><td>   6.42</td><td>2</td><td>76</td><td>222</td><td>10.75</td><td>34.43</td><td>209.89</td><td>  0.770</td><td>24.58</td><td>37.51</td><td>41.19</td><td>309.70</td><td>14.80</td><td> 6.04</td><td>  0.778</td><td>  0.933</td><td>  0.962</td></tr>
<tr><td align="left">007_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 195.68</td><td> 156.39</td><td>2</td><td>76</td><td>222</td><td> 7.89</td><td>33.99</td><td>218.35</td><td>  0.774</td><td>24.41</td><td>36.97</td><td>40.58</td><td>321.63</td><td>16.63</td><td> 6.95</td><td>  0.893</td><td>  0.965</td><td>  0.983</td></tr>
<tr><td align="left">007_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.88</td><td>  10.29</td><td>2</td><td>76</td><td>222</td><td> 8.62</td><td>34.15</td><td>213.85</td><td>  0.777</td><td>24.46</td><td>37.26</td><td>40.72</td><td>315.24</td><td>15.43</td><td> 6.67</td><td>  0.802</td><td>  0.937</td><td>  0.966</td></tr>
<tr><td align="left">007_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.19</td><td>  20.93</td><td>2</td><td>76</td><td>222</td><td> 7.44</td><td>34.03</td><td>215.71</td><td>  0.771</td><td>24.27</td><td>37.08</td><td>40.72</td><td>317.89</td><td>16.04</td><td> 6.66</td><td>  0.820</td><td>  0.941</td><td>  0.969</td></tr>
<tr><td align="left">007_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   4.94</td><td>   3.95</td><td>2</td><td>76</td><td>222</td><td>13.74</td><td>34.66</td><td>204.01</td><td>  0.771</td><td>24.77</td><td>37.83</td><td>41.38</td><td>301.00</td><td>14.12</td><td> 5.92</td><td>  0.768</td><td>  0.928</td><td>  0.958</td></tr>
<tr><td align="left">007_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.80</td><td>  46.99</td><td>2</td><td>76</td><td>222</td><td> 6.94</td><td>34.01</td><td>217.32</td><td>  0.777</td><td>24.37</td><td>37.01</td><td>40.64</td><td>320.24</td><td>16.23</td><td> 6.75</td><td>  0.848</td><td>  0.949</td><td>  0.974</td></tr>
<tr><td align="left">007_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.78</td><td>   6.22</td><td>2</td><td>76</td><td>222</td><td>10.26</td><td>34.34</td><td>209.84</td><td>  0.770</td><td>24.40</td><td>37.46</td><td>41.17</td><td>309.49</td><td>15.00</td><td> 6.08</td><td>  0.777</td><td>  0.932</td><td>  0.962</td></tr>
<tr><td align="left">007_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 197.76</td><td> 158.05</td><td>2</td><td>76</td><td>222</td><td> 7.92</td><td>33.92</td><td>218.25</td><td>  0.774</td><td>24.36</td><td>36.90</td><td>40.52</td><td>321.49</td><td>16.61</td><td> 6.93</td><td>  0.893</td><td>  0.964</td><td>  0.983</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 008
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/008_480p.png)](https://drive.google.com/drive/folders/1I1FJ5gMShqGPSmxBVGmogbO2RkVdyxEN?usp=share_link)\
*__Figure  9__. First Frame of Sequence 008*

Raw Sequence Size: 15.32 GB\
Source: [HERE](https://drive.google.com/drive/folders/1I1FJ5gMShqGPSmxBVGmogbO2RkVdyxEN?usp=share_link)

<br>

*__Table 9__. Description of encoded videos using sequence 008 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">008_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   4.98</td><td>   3.98</td><td>1</td><td>299</td><td>0</td><td>13.37</td><td>30.59</td><td>386.52</td><td>  0.724</td><td>22.01</td><td>33.74</td><td>36.02</td><td>566.14</td><td>34.76</td><td>19.81</td><td>  0.729</td><td>  0.898</td><td>  0.926</td></tr>
<tr><td align="left">008_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.02</td><td>   7.21</td><td>1</td><td>299</td><td>0</td><td>11.23</td><td>30.42</td><td>389.65</td><td>  0.726</td><td>21.97</td><td>33.49</td><td>35.80</td><td>570.30</td><td>36.37</td><td>20.59</td><td>  0.746</td><td>  0.898</td><td>  0.927</td></tr>
<tr><td align="left">008_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.21</td><td>   1.76</td><td>1</td><td>299</td><td>0</td><td>22.66</td><td>31.13</td><td>371.81</td><td>  0.723</td><td>22.31</td><td>34.34</td><td>36.74</td><td>545.50</td><td>31.58</td><td>17.31</td><td>  0.708</td><td>  0.896</td><td>  0.924</td></tr>
<tr><td align="left">008_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  18.48</td><td>  14.77</td><td>1</td><td>299</td><td>0</td><td> 8.49</td><td>30.29</td><td>391.56</td><td>  0.726</td><td>21.93</td><td>33.31</td><td>35.62</td><td>572.73</td><td>37.29</td><td>21.15</td><td>  0.776</td><td>  0.903</td><td>  0.931</td></tr>
<tr><td align="left">008_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.28</td><td>   2.62</td><td>1</td><td>299</td><td>0</td><td>17.80</td><td>30.88</td><td>381.08</td><td>  0.724</td><td>22.12</td><td>34.06</td><td>36.46</td><td>558.96</td><td>33.08</td><td>18.10</td><td>  0.714</td><td>  0.897</td><td>  0.926</td></tr>
<tr><td align="left">008_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  82.33</td><td>  65.79</td><td>1</td><td>299</td><td>0</td><td> 5.23</td><td>30.08</td><td>392.92</td><td>  0.727</td><td>21.92</td><td>33.01</td><td>35.32</td><td>573.94</td><td>39.45</td><td>22.34</td><td>  0.834</td><td>  0.912</td><td>  0.940</td></tr>
<tr><td align="left">008_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.81</td><td>  10.24</td><td>2</td><td>76</td><td>222</td><td>13.17</td><td>30.60</td><td>386.23</td><td>  0.725</td><td>22.00</td><td>33.76</td><td>36.05</td><td>565.91</td><td>34.39</td><td>19.35</td><td>  0.730</td><td>  0.900</td><td>  0.929</td></tr>
<tr><td align="left">008_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  25.95</td><td>  20.74</td><td>2</td><td>76</td><td>222</td><td>11.08</td><td>30.43</td><td>389.24</td><td>  0.726</td><td>21.96</td><td>33.48</td><td>35.83</td><td>569.89</td><td>36.01</td><td>20.13</td><td>  0.746</td><td>  0.899</td><td>  0.929</td></tr>
<tr><td align="left">008_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.25</td><td>   4.99</td><td>2</td><td>76</td><td>222</td><td>22.35</td><td>31.16</td><td>370.84</td><td>  0.723</td><td>22.32</td><td>34.37</td><td>36.79</td><td>544.25</td><td>31.09</td><td>16.93</td><td>  0.708</td><td>  0.896</td><td>  0.925</td></tr>
<tr><td align="left">008_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  59.06</td><td>  47.20</td><td>2</td><td>76</td><td>222</td><td> 8.40</td><td>30.29</td><td>391.85</td><td>  0.726</td><td>21.92</td><td>33.31</td><td>35.64</td><td>573.22</td><td>37.27</td><td>20.93</td><td>  0.775</td><td>  0.902</td><td>  0.932</td></tr>
<tr><td align="left">008_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.43</td><td>   6.74</td><td>2</td><td>76</td><td>222</td><td>17.50</td><td>30.83</td><td>380.17</td><td>  0.724</td><td>22.13</td><td>33.97</td><td>36.39</td><td>557.67</td><td>32.88</td><td>17.97</td><td>  0.713</td><td>  0.897</td><td>  0.927</td></tr>
<tr><td align="left">008_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 203.21</td><td> 162.40</td><td>2</td><td>77</td><td>221</td><td> 5.16</td><td>30.17</td><td>393.58</td><td>  0.727</td><td>21.97</td><td>33.10</td><td>35.44</td><td>575.00</td><td>39.37</td><td>22.10</td><td>  0.831</td><td>  0.911</td><td>  0.942</td></tr>
<tr><td align="left">008_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.93</td><td>  10.33</td><td>2</td><td>76</td><td>222</td><td>13.21</td><td>30.60</td><td>386.05</td><td>  0.725</td><td>22.02</td><td>33.75</td><td>36.05</td><td>565.54</td><td>34.63</td><td>19.53</td><td>  0.730</td><td>  0.898</td><td>  0.928</td></tr>
<tr><td align="left">008_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  25.98</td><td>  20.76</td><td>2</td><td>76</td><td>222</td><td> 9.82</td><td>30.33</td><td>391.00</td><td>  0.724</td><td>21.77</td><td>33.45</td><td>35.77</td><td>572.29</td><td>36.36</td><td>20.48</td><td>  0.743</td><td>  0.897</td><td>  0.927</td></tr>
<tr><td align="left">008_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.33</td><td>   5.06</td><td>2</td><td>76</td><td>222</td><td>22.40</td><td>31.15</td><td>370.85</td><td>  0.723</td><td>22.33</td><td>34.36</td><td>36.76</td><td>544.18</td><td>31.29</td><td>17.11</td><td>  0.708</td><td>  0.895</td><td>  0.924</td></tr>
<tr><td align="left">008_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.84</td><td>  47.02</td><td>2</td><td>76</td><td>222</td><td> 8.40</td><td>30.27</td><td>391.44</td><td>  0.726</td><td>21.94</td><td>33.29</td><td>35.60</td><td>572.49</td><td>37.50</td><td>21.20</td><td>  0.776</td><td>  0.901</td><td>  0.930</td></tr>
<tr><td align="left">008_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.29</td><td>   6.62</td><td>2</td><td>76</td><td>222</td><td>15.18</td><td>30.69</td><td>384.43</td><td>  0.718</td><td>21.80</td><td>33.92</td><td>36.35</td><td>563.75</td><td>33.28</td><td>18.29</td><td>  0.705</td><td>  0.895</td><td>  0.925</td></tr>
<tr><td align="left">008_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 197.35</td><td> 157.73</td><td>2</td><td>76</td><td>222</td><td> 5.20</td><td>30.06</td><td>393.03</td><td>  0.727</td><td>21.92</td><td>32.98</td><td>35.29</td><td>574.05</td><td>39.54</td><td>22.44</td><td>  0.833</td><td>  0.911</td><td>  0.939</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 009
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/009_480p.png)](https://drive.google.com/drive/folders/1C0Cjke5SXXei92v64JNL_GxGWfSP9mb6?usp=sharing)\
*__Figure 10__. First Frame of Sequence 009*

Raw Sequence Size: 15.00 GB\
Source: [HERE](https://drive.google.com/drive/folders/1C0Cjke5SXXei92v64JNL_GxGWfSP9mb6?usp=sharing)

<br>

*__Table 10__. Description of encoded videos using sequence 009 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">009_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.24</td><td>   4.19</td><td>1</td><td>299</td><td>0</td><td>13.03</td><td>40.17</td><td>149.91</td><td>  0.707</td><td>25.25</td><td>45.72</td><td>49.54</td><td>224.23</td><td> 1.81</td><td> 0.74</td><td>  0.620</td><td>  0.980</td><td>  0.991</td></tr>
<tr><td align="left">009_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.61</td><td>   7.68</td><td>1</td><td>299</td><td>0</td><td>10.48</td><td>39.75</td><td>153.02</td><td>  0.723</td><td>25.15</td><td>45.21</td><td>48.90</td><td>228.83</td><td> 2.03</td><td> 0.87</td><td>  0.627</td><td>  0.979</td><td>  0.990</td></tr>
<tr><td align="left">009_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.37</td><td>   1.90</td><td>1</td><td>299</td><td>0</td><td>25.32</td><td>41.17</td><td>134.11</td><td>  0.717</td><td>25.85</td><td>46.95</td><td>50.72</td><td>200.68</td><td> 1.38</td><td> 0.57</td><td>  0.651</td><td>  0.982</td><td>  0.992</td></tr>
<tr><td align="left">009_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  19.22</td><td>  15.36</td><td>1</td><td>299</td><td>0</td><td> 8.84</td><td>39.36</td><td>155.09</td><td>  0.711</td><td>25.10</td><td>44.68</td><td>48.29</td><td>231.81</td><td> 2.29</td><td> 0.99</td><td>  0.657</td><td>  0.978</td><td>  0.989</td></tr>
<tr><td align="left">009_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.49</td><td>   2.79</td><td>1</td><td>299</td><td>0</td><td>17.99</td><td>40.71</td><td>143.57</td><td>  0.720</td><td>25.48</td><td>46.45</td><td>50.19</td><td>214.87</td><td> 1.53</td><td> 0.64</td><td>  0.624</td><td>  0.981</td><td>  0.991</td></tr>
<tr><td align="left">009_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  70.09</td><td>  56.01</td><td>1</td><td>299</td><td>0</td><td> 8.96</td><td>38.74</td><td>156.26</td><td>  0.719</td><td>25.08</td><td>44.04</td><td>47.10</td><td>233.41</td><td> 2.64</td><td> 1.29</td><td>  0.742</td><td>  0.979</td><td>  0.987</td></tr>
<tr><td align="left">009_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.69</td><td>  10.94</td><td>2</td><td>76</td><td>222</td><td>12.86</td><td>39.65</td><td>149.20</td><td>  0.709</td><td>25.27</td><td>45.30</td><td>48.39</td><td>223.07</td><td> 1.97</td><td> 0.96</td><td>  0.621</td><td>  0.981</td><td>  0.990</td></tr>
<tr><td align="left">009_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.91</td><td>  21.51</td><td>2</td><td>76</td><td>222</td><td>10.40</td><td>39.55</td><td>152.63</td><td>  0.724</td><td>25.17</td><td>45.18</td><td>48.32</td><td>228.21</td><td> 2.03</td><td> 0.98</td><td>  0.626</td><td>  0.979</td><td>  0.989</td></tr>
<tr><td align="left">009_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.67</td><td>   5.33</td><td>2</td><td>76</td><td>222</td><td>25.05</td><td>40.73</td><td>133.56</td><td>  0.718</td><td>25.88</td><td>46.69</td><td>49.61</td><td>199.80</td><td> 1.44</td><td> 0.72</td><td>  0.651</td><td>  0.982</td><td>  0.991</td></tr>
<tr><td align="left">009_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  58.65</td><td>  46.87</td><td>2</td><td>76</td><td>222</td><td> 8.82</td><td>39.08</td><td>155.20</td><td>  0.711</td><td>25.09</td><td>44.38</td><td>47.78</td><td>231.91</td><td> 2.43</td><td> 1.11</td><td>  0.655</td><td>  0.978</td><td>  0.988</td></tr>
<tr><td align="left">009_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   9.10</td><td>   7.27</td><td>2</td><td>76</td><td>222</td><td>17.76</td><td>40.39</td><td>142.67</td><td>  0.721</td><td>25.51</td><td>46.19</td><td>49.46</td><td>213.47</td><td> 1.60</td><td> 0.75</td><td>  0.626</td><td>  0.982</td><td>  0.991</td></tr>
<tr><td align="left">009_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 200.91</td><td> 160.57</td><td>3</td><td>76</td><td>221</td><td> 8.99</td><td>38.57</td><td>156.44</td><td>  0.719</td><td>25.15</td><td>43.93</td><td>46.64</td><td>233.61</td><td> 2.73</td><td> 1.45</td><td>  0.738</td><td>  0.978</td><td>  0.985</td></tr>
<tr><td align="left">009_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.26</td><td>  10.60</td><td>2</td><td>76</td><td>222</td><td>12.89</td><td>39.78</td><td>149.16</td><td>  0.709</td><td>25.28</td><td>45.38</td><td>48.69</td><td>223.03</td><td> 1.93</td><td> 0.90</td><td>  0.621</td><td>  0.980</td><td>  0.990</td></tr>
<tr><td align="left">009_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.52</td><td>  21.19</td><td>2</td><td>76</td><td>222</td><td>11.17</td><td>39.66</td><td>150.26</td><td>  0.729</td><td>25.21</td><td>45.16</td><td>48.62</td><td>224.64</td><td> 2.05</td><td> 0.92</td><td>  0.631</td><td>  0.979</td><td>  0.989</td></tr>
<tr><td align="left">009_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.48</td><td>   5.18</td><td>2</td><td>76</td><td>222</td><td>25.09</td><td>40.71</td><td>133.81</td><td>  0.718</td><td>25.88</td><td>46.68</td><td>49.56</td><td>200.16</td><td> 1.45</td><td> 0.73</td><td>  0.650</td><td>  0.982</td><td>  0.991</td></tr>
<tr><td align="left">009_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.82</td><td>  47.81</td><td>2</td><td>76</td><td>222</td><td> 8.82</td><td>39.21</td><td>154.87</td><td>  0.711</td><td>25.12</td><td>44.52</td><td>47.99</td><td>231.45</td><td> 2.36</td><td> 1.06</td><td>  0.657</td><td>  0.978</td><td>  0.988</td></tr>
<tr><td align="left">009_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.98</td><td>   7.18</td><td>2</td><td>76</td><td>222</td><td>19.88</td><td>40.33</td><td>138.70</td><td>  0.731</td><td>25.59</td><td>46.38</td><td>49.03</td><td>207.45</td><td> 1.56</td><td> 0.83</td><td>  0.635</td><td>  0.981</td><td>  0.991</td></tr>
<tr><td align="left">009_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 198.07</td><td> 158.29</td><td>2</td><td>76</td><td>222</td><td> 8.93</td><td>38.61</td><td>156.03</td><td>  0.719</td><td>25.10</td><td>43.92</td><td>46.80</td><td>233.02</td><td> 2.70</td><td> 1.38</td><td>  0.743</td><td>  0.978</td><td>  0.985</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 010
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/010_480p.png)](https://drive.google.com/drive/folders/1t7G9eImxwUE94KxYuRuhk5h5UJohL5ZA?usp=share_link)\
*__Figure 11__. First Frame of Sequence 010*

Raw Sequence Size: 19.83 GB\
Source: [HERE](https://drive.google.com/drive/folders/1t7G9eImxwUE94KxYuRuhk5h5UJohL5ZA?usp=share_link)

<br>

*__Table 11__. Description of encoded videos using sequence 010 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">010_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   4.86</td><td>   3.89</td><td>2</td><td>298</td><td>0</td><td>76.95</td><td>38.57</td><td>327.39</td><td>  0.956</td><td>38.48</td><td>35.19</td><td>42.04</td><td>464.95</td><td>95.19</td><td> 9.34</td><td>  0.940</td><td>  0.913</td><td>  0.960</td></tr>
<tr><td align="left">010_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.26</td><td>   7.40</td><td>2</td><td>298</td><td>0</td><td>77.07</td><td>37.80</td><td>329.46</td><td>  0.956</td><td>37.75</td><td>34.41</td><td>41.24</td><td>467.07</td><td>98.26</td><td>10.40</td><td>  0.932</td><td>  0.895</td><td>  0.951</td></tr>
<tr><td align="left">010_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.18</td><td>   1.74</td><td>2</td><td>298</td><td>0</td><td>76.31</td><td>40.56</td><td>325.79</td><td>  0.956</td><td>40.51</td><td>37.11</td><td>44.07</td><td>463.83</td><td>91.76</td><td> 7.67</td><td>  0.951</td><td>  0.931</td><td>  0.969</td></tr>
<tr><td align="left">010_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  18.98</td><td>  15.17</td><td>2</td><td>298</td><td>0</td><td>76.98</td><td>36.81</td><td>331.19</td><td>  0.956</td><td>36.71</td><td>33.48</td><td>40.25</td><td>468.67</td><td>100.64</td><td>11.80</td><td>  0.915</td><td>  0.865</td><td>  0.935</td></tr>
<tr><td align="left">010_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.17</td><td>   2.53</td><td>2</td><td>298</td><td>0</td><td>75.60</td><td>39.63</td><td>327.24</td><td>  0.956</td><td>39.58</td><td>36.25</td><td>43.07</td><td>465.70</td><td>92.40</td><td> 8.66</td><td>  0.947</td><td>  0.927</td><td>  0.967</td></tr>
<tr><td align="left">010_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  70.46</td><td>  56.31</td><td>1</td><td>299</td><td>0</td><td>72.55</td><td>35.54</td><td>335.42</td><td>  0.956</td><td>35.41</td><td>32.30</td><td>38.92</td><td>472.17</td><td>109.13</td><td>14.73</td><td>  0.885</td><td>  0.819</td><td>  0.910</td></tr>
<tr><td align="left">010_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  10.26</td><td>   8.20</td><td>2</td><td>81</td><td>217</td><td>76.65</td><td>37.74</td><td>328.53</td><td>  0.956</td><td>38.00</td><td>34.18</td><td>41.04</td><td>466.47</td><td>95.59</td><td> 9.71</td><td>  0.938</td><td>  0.903</td><td>  0.956</td></tr>
<tr><td align="left">010_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  21.09</td><td>  16.86</td><td>2</td><td>105</td><td>193</td><td>76.82</td><td>37.14</td><td>328.88</td><td>  0.956</td><td>37.39</td><td>33.52</td><td>40.53</td><td>466.00</td><td>98.84</td><td>10.63</td><td>  0.930</td><td>  0.880</td><td>  0.946</td></tr>
<tr><td align="left">010_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   4.42</td><td>   3.53</td><td>2</td><td>77</td><td>221</td><td>76.12</td><td>39.23</td><td>324.83</td><td>  0.956</td><td>39.84</td><td>35.46</td><td>42.38</td><td>462.12</td><td>92.18</td><td> 8.33</td><td>  0.950</td><td>  0.924</td><td>  0.965</td></tr>
<tr><td align="left">010_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  51.77</td><td>  41.37</td><td>2</td><td>151</td><td>147</td><td>76.48</td><td>36.32</td><td>332.73</td><td>  0.956</td><td>36.44</td><td>32.80</td><td>39.73</td><td>470.52</td><td>102.27</td><td>12.01</td><td>  0.913</td><td>  0.848</td><td>  0.929</td></tr>
<tr><td align="left">010_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   6.62</td><td>   5.29</td><td>2</td><td>80</td><td>218</td><td>75.22</td><td>38.59</td><td>327.75</td><td>  0.956</td><td>38.98</td><td>34.94</td><td>41.85</td><td>466.15</td><td>93.24</td><td> 9.10</td><td>  0.946</td><td>  0.918</td><td>  0.963</td></tr>
<tr><td align="left">010_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 229.48</td><td> 183.40</td><td>5</td><td>77</td><td>218</td><td>70.90</td><td>35.24</td><td>336.31</td><td>  0.956</td><td>34.96</td><td>32.17</td><td>38.59</td><td>473.33</td><td>109.10</td><td>15.42</td><td>  0.875</td><td>  0.816</td><td>  0.903</td></tr>
<tr><td align="left">010_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.26</td><td>   9.79</td><td>2</td><td>76</td><td>222</td><td>76.78</td><td>37.91</td><td>328.48</td><td>  0.956</td><td>38.09</td><td>34.33</td><td>41.31</td><td>466.40</td><td>95.74</td><td> 9.53</td><td>  0.938</td><td>  0.905</td><td>  0.958</td></tr>
<tr><td align="left">010_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  25.23</td><td>  20.17</td><td>2</td><td>76</td><td>222</td><td>67.84</td><td>36.09</td><td>332.48</td><td>  0.955</td><td>33.97</td><td>33.71</td><td>40.60</td><td>471.41</td><td>98.55</td><td>10.69</td><td>  0.916</td><td>  0.886</td><td>  0.948</td></tr>
<tr><td align="left">010_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   4.48</td><td>   3.58</td><td>2</td><td>76</td><td>222</td><td>76.13</td><td>39.33</td><td>324.89</td><td>  0.956</td><td>39.87</td><td>35.56</td><td>42.58</td><td>462.22</td><td>92.20</td><td> 8.26</td><td>  0.950</td><td>  0.925</td><td>  0.966</td></tr>
<tr><td align="left">010_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  57.35</td><td>  45.84</td><td>2</td><td>76</td><td>222</td><td>76.64</td><td>36.43</td><td>332.71</td><td>  0.956</td><td>36.46</td><td>33.00</td><td>39.84</td><td>470.57</td><td>101.81</td><td>12.15</td><td>  0.913</td><td>  0.854</td><td>  0.931</td></tr>
<tr><td align="left">010_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   6.64</td><td>   5.31</td><td>2</td><td>76</td><td>222</td><td>64.81</td><td>36.88</td><td>333.26</td><td>  0.951</td><td>33.65</td><td>35.00</td><td>41.98</td><td>474.28</td><td>93.40</td><td> 9.03</td><td>  0.927</td><td>  0.920</td><td>  0.964</td></tr>
<tr><td align="left">010_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 196.09</td><td> 156.72</td><td>2</td><td>76</td><td>222</td><td>71.92</td><td>35.27</td><td>336.22</td><td>  0.956</td><td>35.19</td><td>32.02</td><td>38.61</td><td>473.23</td><td>109.24</td><td>15.13</td><td>  0.880</td><td>  0.812</td><td>  0.905</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 011
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/011_480p.png)](https://drive.google.com/drive/folders/1jMto-6myikzWCoCo5Y0FrdPDxAuF6V1k?usp=share_link)\
*__Figure 12__. First Frame of Sequence 011*

Raw Sequence Size:  5.78 GB\
Source: [HERE](https://drive.google.com/drive/folders/1jMto-6myikzWCoCo5Y0FrdPDxAuF6V1k?usp=share_link)

<br>

*__Table 12__. Description of encoded videos using sequence 011 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">011_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.28</td><td>   4.22</td><td>2</td><td>298</td><td>0</td><td>24.44</td><td>34.45</td><td>875.28</td><td>  0.736</td><td>24.88</td><td>36.29</td><td>42.17</td><td>1299.42</td><td>44.75</td><td> 9.26</td><td>  0.776</td><td>  0.919</td><td>  0.965</td></tr>
<tr><td align="left">011_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.48</td><td>   8.38</td><td>2</td><td>298</td><td>0</td><td>22.60</td><td>34.30</td><td>878.09</td><td>  0.735</td><td>24.83</td><td>36.16</td><td>41.90</td><td>1303.63</td><td>45.03</td><td> 9.61</td><td>  0.795</td><td>  0.927</td><td>  0.968</td></tr>
<tr><td align="left">011_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.42</td><td>   1.94</td><td>3</td><td>297</td><td>0</td><td>31.99</td><td>34.98</td><td>872.05</td><td>  0.732</td><td>25.14</td><td>36.87</td><td>42.93</td><td>1294.67</td><td>45.12</td><td> 8.50</td><td>  0.734</td><td>  0.907</td><td>  0.959</td></tr>
<tr><td align="left">011_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  23.26</td><td>  18.59</td><td>1</td><td>299</td><td>0</td><td>20.93</td><td>34.22</td><td>876.69</td><td>  0.737</td><td>24.80</td><td>36.08</td><td>41.80</td><td>1301.40</td><td>45.09</td><td> 9.48</td><td>  0.820</td><td>  0.940</td><td>  0.974</td></tr>
<tr><td align="left">011_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.63</td><td>   2.90</td><td>3</td><td>297</td><td>0</td><td>27.34</td><td>34.66</td><td>874.14</td><td>  0.734</td><td>24.97</td><td>36.47</td><td>42.55</td><td>1297.93</td><td>45.59</td><td> 8.74</td><td>  0.753</td><td>  0.911</td><td>  0.961</td></tr>
<tr><td align="left">011_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  92.24</td><td>  73.72</td><td>1</td><td>299</td><td>0</td><td>20.30</td><td>34.12</td><td>877.98</td><td>  0.736</td><td>24.77</td><td>36.01</td><td>41.59</td><td>1303.18</td><td>45.39</td><td> 9.77</td><td>  0.859</td><td>  0.962</td><td>  0.983</td></tr>
<tr><td align="left">011_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.52</td><td>  10.01</td><td>2</td><td>89</td><td>209</td><td>24.29</td><td>34.26</td><td>874.17</td><td>  0.736</td><td>24.84</td><td>36.15</td><td>41.80</td><td>1297.72</td><td>44.86</td><td> 9.28</td><td>  0.776</td><td>  0.919</td><td>  0.965</td></tr>
<tr><td align="left">011_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  24.21</td><td>  19.35</td><td>2</td><td>90</td><td>208</td><td>22.48</td><td>34.21</td><td>879.15</td><td>  0.734</td><td>24.79</td><td>36.10</td><td>41.75</td><td>1305.23</td><td>44.98</td><td> 9.62</td><td>  0.794</td><td>  0.926</td><td>  0.968</td></tr>
<tr><td align="left">011_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   4.76</td><td>   3.80</td><td>2</td><td>89</td><td>209</td><td>31.80</td><td>34.20</td><td>872.00</td><td>  0.732</td><td>25.12</td><td>36.13</td><td>41.34</td><td>1295.05</td><td>42.79</td><td> 9.03</td><td>  0.734</td><td>  0.906</td><td>  0.959</td></tr>
<tr><td align="left">011_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  52.60</td><td>  42.04</td><td>2</td><td>90</td><td>208</td><td>20.89</td><td>34.13</td><td>876.04</td><td>  0.737</td><td>24.77</td><td>36.01</td><td>41.62</td><td>1300.38</td><td>45.20</td><td> 9.54</td><td>  0.820</td><td>  0.939</td><td>  0.973</td></tr>
<tr><td align="left">011_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   7.77</td><td>   6.21</td><td>2</td><td>89</td><td>209</td><td>27.08</td><td>34.02</td><td>872.14</td><td>  0.734</td><td>24.95</td><td>35.95</td><td>41.17</td><td>1295.50</td><td>42.76</td><td> 9.31</td><td>  0.752</td><td>  0.911</td><td>  0.961</td></tr>
<tr><td align="left">011_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 179.43</td><td> 143.40</td><td>3</td><td>82</td><td>215</td><td>20.30</td><td>34.12</td><td>878.02</td><td>  0.736</td><td>24.80</td><td>36.03</td><td>41.54</td><td>1303.19</td><td>45.49</td><td> 9.85</td><td>  0.858</td><td>  0.961</td><td>  0.982</td></tr>
<tr><td align="left">011_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  11.71</td><td>   9.36</td><td>2</td><td>76</td><td>222</td><td>24.27</td><td>34.31</td><td>874.49</td><td>  0.736</td><td>24.84</td><td>36.17</td><td>41.91</td><td>1298.20</td><td>44.84</td><td> 9.27</td><td>  0.776</td><td>  0.919</td><td>  0.965</td></tr>
<tr><td align="left">011_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  23.40</td><td>  18.70</td><td>2</td><td>76</td><td>222</td><td>22.18</td><td>34.20</td><td>878.92</td><td>  0.735</td><td>24.71</td><td>36.11</td><td>41.78</td><td>1304.73</td><td>44.95</td><td> 9.64</td><td>  0.794</td><td>  0.926</td><td>  0.968</td></tr>
<tr><td align="left">011_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   4.12</td><td>   3.29</td><td>2</td><td>76</td><td>222</td><td>31.75</td><td>34.22</td><td>872.42</td><td>  0.732</td><td>25.12</td><td>36.16</td><td>41.38</td><td>1295.68</td><td>42.74</td><td> 9.07</td><td>  0.734</td><td>  0.905</td><td>  0.959</td></tr>
<tr><td align="left">011_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  51.72</td><td>  41.34</td><td>2</td><td>76</td><td>222</td><td>20.87</td><td>34.16</td><td>876.11</td><td>  0.737</td><td>24.77</td><td>36.03</td><td>41.69</td><td>1300.51</td><td>45.10</td><td> 9.52</td><td>  0.820</td><td>  0.939</td><td>  0.974</td></tr>
<tr><td align="left">011_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.03</td><td>   5.62</td><td>2</td><td>76</td><td>222</td><td>26.90</td><td>33.97</td><td>872.03</td><td>  0.735</td><td>24.78</td><td>35.95</td><td>41.18</td><td>1295.00</td><td>42.78</td><td> 9.38</td><td>  0.752</td><td>  0.911</td><td>  0.961</td></tr>
<tr><td align="left">011_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 173.88</td><td> 138.96</td><td>2</td><td>76</td><td>222</td><td>20.30</td><td>34.07</td><td>878.26</td><td>  0.736</td><td>24.76</td><td>35.95</td><td>41.51</td><td>1303.56</td><td>45.53</td><td> 9.81</td><td>  0.858</td><td>  0.962</td><td>  0.983</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 012
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/012_480p.png)](https://drive.google.com/drive/folders/1YLJP1JAUjifGtgSTnVL1Wlx2WPUendTd?usp=share_link)\
*__Figure 13__. First Frame of Sequence 012*

Raw Sequence Size:  5.78 GB\
Source: [HERE](https://drive.google.com/drive/folders/1YLJP1JAUjifGtgSTnVL1Wlx2WPUendTd?usp=share_link)

<br>

*__Table 13__. Description of encoded videos using sequence 012 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">012_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.59</td><td>   4.47</td><td>1</td><td>299</td><td>0</td><td>20.78</td><td>42.61</td><td>110.05</td><td>  0.780</td><td>26.84</td><td>49.89</td><td>51.12</td><td>164.76</td><td> 0.71</td><td> 0.54</td><td>  0.803</td><td>  0.992</td><td>  0.994</td></tr>
<tr><td align="left">012_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.24</td><td>   8.19</td><td>1</td><td>299</td><td>0</td><td>18.72</td><td>42.63</td><td>110.31</td><td>  0.782</td><td>26.84</td><td>50.19</td><td>50.85</td><td>165.18</td><td> 0.65</td><td> 0.57</td><td>  0.826</td><td>  0.993</td><td>  0.994</td></tr>
<tr><td align="left">012_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.48</td><td>   1.98</td><td>1</td><td>299</td><td>0</td><td>27.18</td><td>42.84</td><td>108.60</td><td>  0.777</td><td>26.89</td><td>50.93</td><td>50.71</td><td>162.61</td><td> 0.55</td><td> 0.59</td><td>  0.767</td><td>  0.993</td><td>  0.992</td></tr>
<tr><td align="left">012_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  20.78</td><td>  16.60</td><td>1</td><td>299</td><td>0</td><td>17.68</td><td>42.55</td><td>110.19</td><td>  0.781</td><td>26.85</td><td>49.88</td><td>50.91</td><td>164.96</td><td> 0.70</td><td> 0.57</td><td>  0.863</td><td>  0.994</td><td>  0.995</td></tr>
<tr><td align="left">012_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.72</td><td>   2.97</td><td>1</td><td>299</td><td>0</td><td>23.30</td><td>42.71</td><td>110.20</td><td>  0.780</td><td>26.82</td><td>50.73</td><td>50.58</td><td>165.04</td><td> 0.58</td><td> 0.61</td><td>  0.780</td><td>  0.993</td><td>  0.992</td></tr>
<tr><td align="left">012_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  71.72</td><td>  57.32</td><td>1</td><td>299</td><td>0</td><td>22.14</td><td>42.50</td><td>110.08</td><td>  0.782</td><td>26.87</td><td>50.04</td><td>50.58</td><td>164.80</td><td> 0.68</td><td> 0.61</td><td>  0.925</td><td>  0.996</td><td>  0.996</td></tr>
<tr><td align="left">012_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  10.46</td><td>   8.36</td><td>2</td><td>76</td><td>222</td><td>20.71</td><td>42.11</td><td>110.24</td><td>  0.780</td><td>26.79</td><td>49.65</td><td>49.90</td><td>165.00</td><td> 0.73</td><td> 0.69</td><td>  0.802</td><td>  0.992</td><td>  0.993</td></tr>
<tr><td align="left">012_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  18.31</td><td>  14.63</td><td>2</td><td>76</td><td>222</td><td>18.60</td><td>41.68</td><td>110.39</td><td>  0.782</td><td>26.80</td><td>49.90</td><td>48.32</td><td>165.18</td><td> 0.69</td><td> 0.98</td><td>  0.825</td><td>  0.993</td><td>  0.993</td></tr>
<tr><td align="left">012_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   3.98</td><td>   3.18</td><td>2</td><td>76</td><td>222</td><td>26.91</td><td>42.09</td><td>108.13</td><td>  0.778</td><td>26.86</td><td>50.31</td><td>49.09</td><td>161.83</td><td> 0.62</td><td> 0.82</td><td>  0.767</td><td>  0.992</td><td>  0.992</td></tr>
<tr><td align="left">012_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  37.37</td><td>  29.87</td><td>2</td><td>76</td><td>222</td><td>17.66</td><td>42.01</td><td>110.50</td><td>  0.781</td><td>26.80</td><td>49.04</td><td>50.19</td><td>165.37</td><td> 0.83</td><td> 0.66</td><td>  0.861</td><td>  0.993</td><td>  0.994</td></tr>
<tr><td align="left">012_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   6.46</td><td>   5.16</td><td>2</td><td>76</td><td>222</td><td>23.03</td><td>42.18</td><td>109.99</td><td>  0.780</td><td>26.80</td><td>50.32</td><td>49.43</td><td>164.68</td><td> 0.62</td><td> 0.77</td><td>  0.779</td><td>  0.992</td><td>  0.992</td></tr>
<tr><td align="left">012_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 188.63</td><td> 150.75</td><td>2</td><td>76</td><td>222</td><td>22.12</td><td>42.29</td><td>110.25</td><td>  0.782</td><td>26.88</td><td>49.78</td><td>50.20</td><td>165.03</td><td> 0.72</td><td> 0.67</td><td>  0.924</td><td>  0.996</td><td>  0.996</td></tr>
<tr><td align="left">012_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  10.85</td><td>   8.67</td><td>2</td><td>76</td><td>222</td><td>20.71</td><td>42.21</td><td>110.06</td><td>  0.781</td><td>26.79</td><td>49.78</td><td>50.05</td><td>164.75</td><td> 0.71</td><td> 0.67</td><td>  0.803</td><td>  0.992</td><td>  0.993</td></tr>
<tr><td align="left">012_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  17.70</td><td>  14.14</td><td>2</td><td>76</td><td>222</td><td>19.49</td><td>41.71</td><td>108.67</td><td>  0.787</td><td>26.82</td><td>50.01</td><td>48.29</td><td>162.60</td><td> 0.67</td><td> 0.98</td><td>  0.829</td><td>  0.993</td><td>  0.993</td></tr>
<tr><td align="left">012_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   3.84</td><td>   3.07</td><td>2</td><td>76</td><td>222</td><td>26.91</td><td>42.06</td><td>108.09</td><td>  0.778</td><td>26.86</td><td>50.28</td><td>49.02</td><td>161.77</td><td> 0.63</td><td> 0.83</td><td>  0.768</td><td>  0.992</td><td>  0.992</td></tr>
<tr><td align="left">012_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  32.96</td><td>  26.35</td><td>2</td><td>76</td><td>222</td><td>17.62</td><td>42.17</td><td>110.29</td><td>  0.781</td><td>26.81</td><td>49.26</td><td>50.43</td><td>165.07</td><td> 0.79</td><td> 0.63</td><td>  0.862</td><td>  0.993</td><td>  0.994</td></tr>
<tr><td align="left">012_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   6.12</td><td>   4.89</td><td>2</td><td>76</td><td>222</td><td>25.09</td><td>42.23</td><td>106.90</td><td>  0.789</td><td>26.83</td><td>50.44</td><td>49.44</td><td>160.01</td><td> 0.61</td><td> 0.76</td><td>  0.789</td><td>  0.992</td><td>  0.992</td></tr>
<tr><td align="left">012_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 102.88</td><td>  82.22</td><td>2</td><td>76</td><td>222</td><td>22.09</td><td>42.21</td><td>110.20</td><td>  0.782</td><td>26.85</td><td>49.88</td><td>49.90</td><td>164.95</td><td> 0.70</td><td> 0.70</td><td>  0.924</td><td>  0.996</td><td>  0.996</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 013
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/013_480p.png)](https://drive.google.com/drive/folders/1BW78JWK1FURwVFlbO9wobWGxfvC5M-qt?usp=sharing)\
*__Figure 14__. First Frame of Sequence 013*

Raw Sequence Size:  9.86 GB\
Source: [HERE](https://drive.google.com/drive/folders/1BW78JWK1FURwVFlbO9wobWGxfvC5M-qt?usp=sharing)

<br>

*__Table 14__. Description of encoded videos using sequence 013 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">013_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.58</td><td>   4.46</td><td>1</td><td>299</td><td>0</td><td>54.46</td><td>35.38</td><td>175.29</td><td>  0.856</td><td>25.78</td><td>37.34</td><td>43.03</td><td>258.43</td><td>14.62</td><td> 3.37</td><td>  0.888</td><td>  0.935</td><td>  0.972</td></tr>
<tr><td align="left">013_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  11.31</td><td>   9.04</td><td>1</td><td>299</td><td>0</td><td>53.43</td><td>35.12</td><td>175.35</td><td>  0.855</td><td>25.78</td><td>37.01</td><td>42.56</td><td>258.29</td><td>15.32</td><td> 3.73</td><td>  0.903</td><td>  0.931</td><td>  0.969</td></tr>
<tr><td align="left">013_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.37</td><td>   1.89</td><td>1</td><td>299</td><td>0</td><td>56.14</td><td>36.09</td><td>174.36</td><td>  0.853</td><td>25.80</td><td>38.30</td><td>44.18</td><td>257.67</td><td>12.83</td><td> 2.66</td><td>  0.854</td><td>  0.948</td><td>  0.978</td></tr>
<tr><td align="left">013_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  26.71</td><td>  21.35</td><td>1</td><td>299</td><td>0</td><td>52.27</td><td>34.95</td><td>175.62</td><td>  0.856</td><td>25.79</td><td>36.74</td><td>42.32</td><td>258.42</td><td>16.11</td><td> 3.94</td><td>  0.925</td><td>  0.930</td><td>  0.969</td></tr>
<tr><td align="left">013_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.48</td><td>   2.78</td><td>1</td><td>299</td><td>0</td><td>55.41</td><td>35.77</td><td>174.86</td><td>  0.854</td><td>25.78</td><td>37.78</td><td>43.76</td><td>258.22</td><td>13.65</td><td> 2.86</td><td>  0.868</td><td>  0.941</td><td>  0.975</td></tr>
<tr><td align="left">013_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  95.54</td><td>  76.36</td><td>1</td><td>299</td><td>0</td><td>54.33</td><td>34.69</td><td>176.14</td><td>  0.854</td><td>25.79</td><td>36.47</td><td>41.79</td><td>258.83</td><td>17.05</td><td> 4.46</td><td>  0.955</td><td>  0.946</td><td>  0.975</td></tr>
<tr><td align="left">013_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  14.09</td><td>  11.26</td><td>2</td><td>76</td><td>222</td><td>54.17</td><td>34.99</td><td>175.84</td><td>  0.855</td><td>25.75</td><td>36.94</td><td>42.28</td><td>258.86</td><td>15.60</td><td> 3.97</td><td>  0.884</td><td>  0.924</td><td>  0.966</td></tr>
<tr><td align="left">013_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  28.32</td><td>  22.63</td><td>2</td><td>76</td><td>222</td><td>53.22</td><td>34.85</td><td>175.97</td><td>  0.854</td><td>25.77</td><td>36.72</td><td>42.06</td><td>258.88</td><td>16.22</td><td> 4.17</td><td>  0.900</td><td>  0.921</td><td>  0.963</td></tr>
<tr><td align="left">013_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.83</td><td>   5.46</td><td>2</td><td>76</td><td>222</td><td>55.94</td><td>35.70</td><td>174.76</td><td>  0.852</td><td>25.79</td><td>37.85</td><td>43.46</td><td>257.98</td><td>13.57</td><td> 3.08</td><td>  0.851</td><td>  0.937</td><td>  0.972</td></tr>
<tr><td align="left">013_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  63.59</td><td>  50.82</td><td>2</td><td>76</td><td>222</td><td>52.28</td><td>34.70</td><td>176.35</td><td>  0.855</td><td>25.77</td><td>36.54</td><td>41.80</td><td>259.23</td><td>16.78</td><td> 4.42</td><td>  0.922</td><td>  0.923</td><td>  0.964</td></tr>
<tr><td align="left">013_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   9.11</td><td>   7.28</td><td>2</td><td>76</td><td>222</td><td>55.18</td><td>35.39</td><td>175.43</td><td>  0.853</td><td>25.76</td><td>37.37</td><td>43.04</td><td>258.73</td><td>14.55</td><td> 3.35</td><td>  0.865</td><td>  0.930</td><td>  0.969</td></tr>
<tr><td align="left">013_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 202.74</td><td> 162.03</td><td>2</td><td>180</td><td>118</td><td>54.32</td><td>34.62</td><td>176.58</td><td>  0.854</td><td>25.83</td><td>36.44</td><td>41.59</td><td>259.31</td><td>17.49</td><td> 4.74</td><td>  0.953</td><td>  0.942</td><td>  0.972</td></tr>
<tr><td align="left">013_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.17</td><td>  10.53</td><td>2</td><td>76</td><td>222</td><td>53.99</td><td>35.04</td><td>175.69</td><td>  0.855</td><td>25.77</td><td>36.97</td><td>42.38</td><td>258.68</td><td>15.54</td><td> 3.89</td><td>  0.885</td><td>  0.925</td><td>  0.967</td></tr>
<tr><td align="left">013_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.20</td><td>  20.94</td><td>2</td><td>76</td><td>222</td><td>49.75</td><td>34.81</td><td>176.76</td><td>  0.853</td><td>25.61</td><td>36.74</td><td>42.08</td><td>260.05</td><td>16.18</td><td> 4.16</td><td>  0.898</td><td>  0.921</td><td>  0.963</td></tr>
<tr><td align="left">013_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.74</td><td>   5.39</td><td>2</td><td>76</td><td>222</td><td>55.86</td><td>35.77</td><td>174.58</td><td>  0.852</td><td>25.79</td><td>37.89</td><td>43.62</td><td>257.75</td><td>13.51</td><td> 2.98</td><td>  0.851</td><td>  0.938</td><td>  0.973</td></tr>
<tr><td align="left">013_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.83</td><td>  47.02</td><td>2</td><td>76</td><td>222</td><td>52.15</td><td>34.72</td><td>176.24</td><td>  0.855</td><td>25.78</td><td>36.56</td><td>41.82</td><td>259.06</td><td>16.77</td><td> 4.41</td><td>  0.922</td><td>  0.923</td><td>  0.964</td></tr>
<tr><td align="left">013_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   9.10</td><td>   7.28</td><td>2</td><td>76</td><td>222</td><td>48.39</td><td>35.30</td><td>179.26</td><td>  0.848</td><td>25.36</td><td>37.40</td><td>43.16</td><td>264.45</td><td>14.49</td><td> 3.27</td><td>  0.857</td><td>  0.931</td><td>  0.970</td></tr>
<tr><td align="left">013_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 199.43</td><td> 159.38</td><td>2</td><td>76</td><td>222</td><td>54.30</td><td>34.56</td><td>176.59</td><td>  0.854</td><td>25.78</td><td>36.35</td><td>41.55</td><td>259.34</td><td>17.50</td><td> 4.71</td><td>  0.954</td><td>  0.942</td><td>  0.972</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 014
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/014_480p.png)](https://drive.google.com/drive/folders/1Jjdrihc_lPh_ABPRZVbvOGJaPsLwYji5?usp=share_link)\
*__Figure 15__. First Frame of Sequence 014*

Raw Sequence Size: 11.99 GB\
Source: [HERE](https://drive.google.com/drive/folders/1Jjdrihc_lPh_ABPRZVbvOGJaPsLwYji5?usp=share_link)

<br>

*__Table 15__. Description of encoded videos using sequence 014 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">014_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.98</td><td>   4.78</td><td>1</td><td>299</td><td>0</td><td>10.06</td><td>31.85</td><td>584.60</td><td>  0.547</td><td>19.49</td><td>35.34</td><td>40.73</td><td>869.97</td><td>21.48</td><td> 6.20</td><td>  0.698</td><td>  0.942</td><td>  0.977</td></tr>
<tr><td align="left">014_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.93</td><td>   8.73</td><td>1</td><td>299</td><td>0</td><td>10.06</td><td>31.96</td><td>585.51</td><td>  0.527</td><td>19.49</td><td>35.47</td><td>40.91</td><td>871.70</td><td>20.74</td><td> 5.96</td><td>  0.739</td><td>  0.952</td><td>  0.979</td></tr>
<tr><td align="left">014_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.59</td><td>   2.07</td><td>1</td><td>299</td><td>0</td><td>11.02</td><td>32.06</td><td>580.63</td><td>  0.526</td><td>19.56</td><td>35.49</td><td>41.12</td><td>864.21</td><td>21.08</td><td> 5.86</td><td>  0.559</td><td>  0.913</td><td>  0.971</td></tr>
<tr><td align="left">014_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  24.18</td><td>  19.32</td><td>2</td><td>298</td><td>0</td><td>11.47</td><td>31.67</td><td>587.41</td><td>  0.544</td><td>19.48</td><td>35.32</td><td>40.20</td><td>874.07</td><td>21.34</td><td> 6.87</td><td>  0.793</td><td>  0.961</td><td>  0.980</td></tr>
<tr><td align="left">014_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   4.03</td><td>   3.22</td><td>1</td><td>299</td><td>0</td><td>10.31</td><td>32.00</td><td>582.10</td><td>  0.528</td><td>19.52</td><td>35.87</td><td>40.62</td><td>866.98</td><td>19.07</td><td> 6.44</td><td>  0.630</td><td>  0.933</td><td>  0.973</td></tr>
<tr><td align="left">014_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  86.86</td><td>  69.42</td><td>1</td><td>299</td><td>0</td><td>18.48</td><td>31.48</td><td>587.95</td><td>  0.534</td><td>19.51</td><td>35.12</td><td>39.83</td><td>874.51</td><td>22.28</td><td> 7.41</td><td>  0.869</td><td>  0.973</td><td>  0.981</td></tr>
<tr><td align="left">014_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.75</td><td>  10.19</td><td>2</td><td>183</td><td>115</td><td>10.16</td><td>31.84</td><td>584.48</td><td>  0.548</td><td>19.52</td><td>35.48</td><td>40.53</td><td>869.91</td><td>20.75</td><td> 6.48</td><td>  0.697</td><td>  0.945</td><td>  0.977</td></tr>
<tr><td align="left">014_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  25.68</td><td>  20.53</td><td>2</td><td>214</td><td>84</td><td>10.11</td><td>31.89</td><td>584.93</td><td>  0.527</td><td>19.52</td><td>35.52</td><td>40.63</td><td>870.77</td><td>20.60</td><td> 6.30</td><td>  0.739</td><td>  0.953</td><td>  0.979</td></tr>
<tr><td align="left">014_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.54</td><td>   5.22</td><td>2</td><td>101</td><td>197</td><td>11.11</td><td>32.06</td><td>580.39</td><td>  0.525</td><td>19.59</td><td>35.65</td><td>40.94</td><td>864.02</td><td>20.28</td><td> 5.96</td><td>  0.555</td><td>  0.916</td><td>  0.970</td></tr>
<tr><td align="left">014_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  57.97</td><td>  46.33</td><td>2</td><td>244</td><td>54</td><td>11.55</td><td>31.65</td><td>587.61</td><td>  0.544</td><td>19.51</td><td>35.32</td><td>40.11</td><td>874.31</td><td>21.40</td><td> 7.01</td><td>  0.791</td><td>  0.961</td><td>  0.979</td></tr>
<tr><td align="left">014_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.44</td><td>   6.74</td><td>2</td><td>135</td><td>163</td><td>10.37</td><td>32.04</td><td>582.46</td><td>  0.528</td><td>19.54</td><td>35.85</td><td>40.72</td><td>867.53</td><td>19.23</td><td> 6.25</td><td>  0.628</td><td>  0.934</td><td>  0.973</td></tr>
<tr><td align="left">014_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 191.13</td><td> 152.75</td><td>32</td><td>208</td><td>60</td><td>18.69</td><td>31.55</td><td>588.04</td><td>  0.534</td><td>19.59</td><td>35.20</td><td>39.86</td><td>874.60</td><td>22.34</td><td> 7.49</td><td>  0.867</td><td>  0.973</td><td>  0.981</td></tr>
<tr><td align="left">014_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.28</td><td>  10.61</td><td>2</td><td>76</td><td>222</td><td>10.23</td><td>31.80</td><td>585.24</td><td>  0.546</td><td>19.53</td><td>35.38</td><td>40.50</td><td>870.90</td><td>21.32</td><td> 6.54</td><td>  0.692</td><td>  0.942</td><td>  0.975</td></tr>
<tr><td align="left">014_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.59</td><td>  21.25</td><td>2</td><td>76</td><td>222</td><td>10.20</td><td>31.82</td><td>585.55</td><td>  0.526</td><td>19.52</td><td>35.41</td><td>40.54</td><td>871.43</td><td>21.17</td><td> 6.44</td><td>  0.734</td><td>  0.950</td><td>  0.977</td></tr>
<tr><td align="left">014_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.84</td><td>   5.46</td><td>2</td><td>76</td><td>222</td><td>11.08</td><td>32.03</td><td>579.81</td><td>  0.525</td><td>19.60</td><td>35.59</td><td>40.91</td><td>863.06</td><td>20.60</td><td> 6.00</td><td>  0.555</td><td>  0.913</td><td>  0.969</td></tr>
<tr><td align="left">014_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  60.35</td><td>  48.23</td><td>2</td><td>76</td><td>222</td><td>11.58</td><td>31.60</td><td>587.92</td><td>  0.544</td><td>19.52</td><td>35.25</td><td>40.04</td><td>874.66</td><td>21.76</td><td> 7.12</td><td>  0.789</td><td>  0.959</td><td>  0.977</td></tr>
<tr><td align="left">014_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.93</td><td>   7.14</td><td>2</td><td>76</td><td>222</td><td>10.53</td><td>31.96</td><td>582.65</td><td>  0.527</td><td>19.53</td><td>35.73</td><td>40.62</td><td>867.42</td><td>19.80</td><td> 6.39</td><td>  0.625</td><td>  0.930</td><td>  0.971</td></tr>
<tr><td align="left">014_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 204.92</td><td> 163.77</td><td>2</td><td>76</td><td>222</td><td>18.72</td><td>31.43</td><td>588.46</td><td>  0.533</td><td>19.52</td><td>35.09</td><td>39.68</td><td>875.16</td><td>22.43</td><td> 7.65</td><td>  0.866</td><td>  0.972</td><td>  0.979</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 015
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/015_480p.png)](https://drive.google.com/drive/folders/1quWkHPelIIjqnNuEzBwE_PXGWTcGsRHj?usp=share_link)\
*__Figure 16__. First Frame of Sequence 015*

Raw Sequence Size:  9.66 GB\
Source: [HERE](https://drive.google.com/drive/folders/1quWkHPelIIjqnNuEzBwE_PXGWTcGsRHj?usp=share_link)

<br>

*__Table 16__. Description of encoded videos using sequence 015 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">015_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.39</td><td>   4.30</td><td>1</td><td>299</td><td>0</td><td> 4.10</td><td>30.94</td><td>558.17</td><td>  0.641</td><td>20.81</td><td>36.82</td><td>35.20</td><td>827.09</td><td>16.11</td><td>24.53</td><td>  0.757</td><td>  0.943</td><td>  0.940</td></tr>
<tr><td align="left">015_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.87</td><td>   8.69</td><td>1</td><td>299</td><td>0</td><td> 3.65</td><td>30.83</td><td>558.64</td><td>  0.629</td><td>20.81</td><td>36.60</td><td>35.07</td><td>827.59</td><td>16.81</td><td>25.07</td><td>  0.794</td><td>  0.943</td><td>  0.944</td></tr>
<tr><td align="left">015_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.30</td><td>   1.84</td><td>1</td><td>299</td><td>0</td><td> 7.12</td><td>31.30</td><td>553.79</td><td>  0.626</td><td>20.89</td><td>37.37</td><td>35.64</td><td>821.19</td><td>14.83</td><td>23.13</td><td>  0.652</td><td>  0.938</td><td>  0.927</td></tr>
<tr><td align="left">015_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  24.74</td><td>  19.77</td><td>1</td><td>299</td><td>0</td><td> 3.21</td><td>30.81</td><td>558.68</td><td>  0.641</td><td>20.81</td><td>36.55</td><td>35.06</td><td>827.55</td><td>16.89</td><td>24.99</td><td>  0.841</td><td>  0.948</td><td>  0.953</td></tr>
<tr><td align="left">015_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.48</td><td>   2.78</td><td>1</td><td>299</td><td>0</td><td> 5.30</td><td>31.13</td><td>556.94</td><td>  0.628</td><td>20.83</td><td>37.15</td><td>35.41</td><td>825.87</td><td>15.22</td><td>23.73</td><td>  0.703</td><td>  0.941</td><td>  0.933</td></tr>
<tr><td align="left">015_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  89.21</td><td>  71.29</td><td>1</td><td>299</td><td>0</td><td> 2.88</td><td>30.70</td><td>559.11</td><td>  0.634</td><td>20.83</td><td>36.34</td><td>34.94</td><td>827.82</td><td>17.71</td><td>25.66</td><td>  0.902</td><td>  0.962</td><td>  0.967</td></tr>
<tr><td align="left">015_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  14.58</td><td>  11.65</td><td>2</td><td>81</td><td>217</td><td> 4.08</td><td>30.84</td><td>558.74</td><td>  0.640</td><td>20.81</td><td>36.62</td><td>35.10</td><td>827.72</td><td>16.64</td><td>24.89</td><td>  0.754</td><td>  0.937</td><td>  0.937</td></tr>
<tr><td align="left">015_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  29.20</td><td>  23.34</td><td>2</td><td>89</td><td>209</td><td> 3.65</td><td>30.78</td><td>558.78</td><td>  0.628</td><td>20.82</td><td>36.48</td><td>35.04</td><td>827.68</td><td>17.19</td><td>25.17</td><td>  0.791</td><td>  0.937</td><td>  0.941</td></tr>
<tr><td align="left">015_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.82</td><td>   5.45</td><td>2</td><td>76</td><td>222</td><td> 7.11</td><td>31.24</td><td>553.44</td><td>  0.624</td><td>20.91</td><td>37.24</td><td>35.58</td><td>820.62</td><td>15.12</td><td>23.06</td><td>  0.648</td><td>  0.933</td><td>  0.926</td></tr>
<tr><td align="left">015_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  65.65</td><td>  52.47</td><td>2</td><td>92</td><td>206</td><td> 3.20</td><td>30.73</td><td>559.86</td><td>  0.640</td><td>20.82</td><td>36.39</td><td>34.97</td><td>829.08</td><td>17.44</td><td>25.39</td><td>  0.838</td><td>  0.943</td><td>  0.949</td></tr>
<tr><td align="left">015_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   9.25</td><td>   7.39</td><td>2</td><td>77</td><td>221</td><td> 5.27</td><td>31.09</td><td>556.88</td><td>  0.627</td><td>20.84</td><td>37.01</td><td>35.42</td><td>825.71</td><td>15.60</td><td>23.60</td><td>  0.699</td><td>  0.936</td><td>  0.932</td></tr>
<tr><td align="left">015_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 207.96</td><td> 166.20</td><td>5</td><td>85</td><td>210</td><td> 2.86</td><td>30.72</td><td>560.19</td><td>  0.633</td><td>20.89</td><td>36.31</td><td>34.95</td><td>829.24</td><td>18.18</td><td>25.99</td><td>  0.899</td><td>  0.958</td><td>  0.964</td></tr>
<tr><td align="left">015_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.12</td><td>  10.49</td><td>2</td><td>76</td><td>222</td><td> 4.09</td><td>30.85</td><td>558.46</td><td>  0.640</td><td>20.83</td><td>36.63</td><td>35.10</td><td>827.30</td><td>16.68</td><td>24.90</td><td>  0.754</td><td>  0.936</td><td>  0.937</td></tr>
<tr><td align="left">015_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.25</td><td>  20.98</td><td>2</td><td>76</td><td>222</td><td> 3.59</td><td>30.76</td><td>558.10</td><td>  0.629</td><td>20.78</td><td>36.47</td><td>35.04</td><td>826.53</td><td>17.30</td><td>25.20</td><td>  0.790</td><td>  0.937</td><td>  0.941</td></tr>
<tr><td align="left">015_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.75</td><td>   5.39</td><td>2</td><td>76</td><td>222</td><td> 7.10</td><td>31.22</td><td>553.24</td><td>  0.625</td><td>20.91</td><td>37.21</td><td>35.55</td><td>820.24</td><td>15.25</td><td>23.23</td><td>  0.650</td><td>  0.932</td><td>  0.925</td></tr>
<tr><td align="left">015_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.08</td><td>  47.22</td><td>2</td><td>76</td><td>222</td><td> 3.20</td><td>30.74</td><td>559.63</td><td>  0.640</td><td>20.83</td><td>36.39</td><td>34.98</td><td>828.72</td><td>17.49</td><td>25.40</td><td>  0.838</td><td>  0.942</td><td>  0.948</td></tr>
<tr><td align="left">015_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   9.13</td><td>   7.29</td><td>2</td><td>76</td><td>222</td><td> 5.33</td><td>31.04</td><td>555.86</td><td>  0.628</td><td>20.78</td><td>36.97</td><td>35.38</td><td>823.93</td><td>15.77</td><td>23.68</td><td>  0.701</td><td>  0.935</td><td>  0.931</td></tr>
<tr><td align="left">015_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 198.90</td><td> 158.96</td><td>2</td><td>76</td><td>222</td><td> 2.87</td><td>30.65</td><td>560.13</td><td>  0.633</td><td>20.83</td><td>36.23</td><td>34.88</td><td>829.16</td><td>18.15</td><td>25.98</td><td>  0.900</td><td>  0.958</td><td>  0.965</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 016
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/016_480p.png)](https://drive.google.com/drive/folders/1Bvk4CJpKb820Iwje3RbnG0SoilaKO8lc?usp=share_link)\
*__Figure 17__. First Frame of Sequence 016*

Raw Sequence Size:  7.85 GB\
Source: [HERE](https://drive.google.com/drive/folders/1Bvk4CJpKb820Iwje3RbnG0SoilaKO8lc?usp=share_link)

<br>

*__Table 17__. Description of encoded videos using sequence 016 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">016_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.27</td><td>   4.21</td><td>1</td><td>299</td><td>0</td><td> 5.92</td><td>34.18</td><td>116.70</td><td>  0.718</td><td>26.39</td><td>38.12</td><td>38.02</td><td>169.30</td><td>11.02</td><td>11.95</td><td>  0.761</td><td>  0.937</td><td>  0.946</td></tr>
<tr><td align="left">016_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.79</td><td>   7.82</td><td>1</td><td>299</td><td>0</td><td> 4.59</td><td>34.09</td><td>116.99</td><td>  0.722</td><td>26.40</td><td>37.98</td><td>37.89</td><td>169.60</td><td>11.35</td><td>12.26</td><td>  0.795</td><td>  0.942</td><td>  0.950</td></tr>
<tr><td align="left">016_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.41</td><td>   1.93</td><td>1</td><td>299</td><td>0</td><td>13.61</td><td>34.68</td><td>112.71</td><td>  0.717</td><td>26.54</td><td>38.84</td><td>38.66</td><td>163.99</td><td> 9.57</td><td>10.74</td><td>  0.696</td><td>  0.935</td><td>  0.942</td></tr>
<tr><td align="left">016_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  20.86</td><td>  16.67</td><td>1</td><td>299</td><td>0</td><td> 3.66</td><td>34.10</td><td>117.15</td><td>  0.719</td><td>26.41</td><td>37.98</td><td>37.90</td><td>169.83</td><td>11.38</td><td>12.22</td><td>  0.845</td><td>  0.952</td><td>  0.959</td></tr>
<tr><td align="left">016_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.54</td><td>   2.83</td><td>1</td><td>299</td><td>0</td><td> 8.59</td><td>34.35</td><td>115.55</td><td>  0.719</td><td>26.42</td><td>38.40</td><td>38.22</td><td>167.88</td><td>10.40</td><td>11.56</td><td>  0.720</td><td>  0.934</td><td>  0.942</td></tr>
<tr><td align="left">016_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  92.24</td><td>  73.72</td><td>1</td><td>299</td><td>0</td><td> 3.55</td><td>34.03</td><td>117.36</td><td>  0.721</td><td>26.43</td><td>37.87</td><td>37.80</td><td>169.98</td><td>11.70</td><td>12.51</td><td>  0.919</td><td>  0.970</td><td>  0.974</td></tr>
<tr><td align="left">016_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.65</td><td>  10.91</td><td>2</td><td>76</td><td>222</td><td> 5.89</td><td>34.19</td><td>116.62</td><td>  0.718</td><td>26.39</td><td>38.14</td><td>38.02</td><td>169.26</td><td>10.86</td><td>11.84</td><td>  0.760</td><td>  0.938</td><td>  0.946</td></tr>
<tr><td align="left">016_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  27.78</td><td>  22.20</td><td>2</td><td>76</td><td>222</td><td> 4.60</td><td>34.10</td><td>117.20</td><td>  0.722</td><td>26.39</td><td>38.02</td><td>37.89</td><td>169.99</td><td>11.18</td><td>12.15</td><td>  0.793</td><td>  0.941</td><td>  0.949</td></tr>
<tr><td align="left">016_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.71</td><td>   5.37</td><td>2</td><td>76</td><td>222</td><td>13.45</td><td>34.70</td><td>112.56</td><td>  0.716</td><td>26.55</td><td>38.92</td><td>38.63</td><td>163.89</td><td> 9.24</td><td>10.55</td><td>  0.694</td><td>  0.937</td><td>  0.943</td></tr>
<tr><td align="left">016_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  60.62</td><td>  48.45</td><td>2</td><td>76</td><td>222</td><td> 3.68</td><td>34.00</td><td>117.61</td><td>  0.718</td><td>26.40</td><td>37.85</td><td>37.77</td><td>170.39</td><td>11.63</td><td>12.49</td><td>  0.843</td><td>  0.949</td><td>  0.956</td></tr>
<tr><td align="left">016_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   9.01</td><td>   7.20</td><td>2</td><td>76</td><td>222</td><td> 8.54</td><td>34.49</td><td>115.25</td><td>  0.719</td><td>26.43</td><td>38.61</td><td>38.42</td><td>167.74</td><td> 9.79</td><td>10.92</td><td>  0.719</td><td>  0.937</td><td>  0.945</td></tr>
<tr><td align="left">016_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 196.63</td><td> 157.15</td><td>3</td><td>76</td><td>221</td><td> 3.55</td><td>34.04</td><td>117.60</td><td>  0.720</td><td>26.47</td><td>37.86</td><td>37.79</td><td>170.26</td><td>11.88</td><td>12.69</td><td>  0.917</td><td>  0.968</td><td>  0.972</td></tr>
<tr><td align="left">016_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.24</td><td>  10.58</td><td>2</td><td>76</td><td>222</td><td> 5.89</td><td>34.14</td><td>116.50</td><td>  0.718</td><td>26.41</td><td>38.06</td><td>37.96</td><td>168.96</td><td>11.11</td><td>12.03</td><td>  0.760</td><td>  0.937</td><td>  0.945</td></tr>
<tr><td align="left">016_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.48</td><td>  21.16</td><td>2</td><td>76</td><td>222</td><td> 4.28</td><td>34.06</td><td>115.91</td><td>  0.724</td><td>26.37</td><td>37.97</td><td>37.85</td><td>167.95</td><td>11.34</td><td>12.28</td><td>  0.794</td><td>  0.940</td><td>  0.948</td></tr>
<tr><td align="left">016_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.64</td><td>   5.30</td><td>2</td><td>76</td><td>222</td><td>13.47</td><td>34.63</td><td>112.43</td><td>  0.717</td><td>26.56</td><td>38.80</td><td>38.54</td><td>163.55</td><td> 9.56</td><td>10.84</td><td>  0.695</td><td>  0.935</td><td>  0.941</td></tr>
<tr><td align="left">016_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.19</td><td>  47.31</td><td>2</td><td>76</td><td>222</td><td> 3.68</td><td>34.01</td><td>117.44</td><td>  0.719</td><td>26.41</td><td>37.86</td><td>37.77</td><td>170.12</td><td>11.65</td><td>12.51</td><td>  0.844</td><td>  0.949</td><td>  0.956</td></tr>
<tr><td align="left">016_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.66</td><td>   6.92</td><td>2</td><td>76</td><td>222</td><td> 8.49</td><td>34.40</td><td>113.02</td><td>  0.724</td><td>26.41</td><td>38.48</td><td>38.31</td><td>164.19</td><td>10.16</td><td>11.24</td><td>  0.722</td><td>  0.935</td><td>  0.943</td></tr>
<tr><td align="left">016_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 196.70</td><td> 157.20</td><td>2</td><td>76</td><td>222</td><td> 3.56</td><td>33.99</td><td>117.64</td><td>  0.720</td><td>26.43</td><td>37.81</td><td>37.72</td><td>170.32</td><td>11.83</td><td>12.68</td><td>  0.918</td><td>  0.969</td><td>  0.972</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 017
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/017_480p.png)](https://drive.google.com/drive/folders/17sLpoKqUAQhiLmESB4niZ0b9vrQ51YHG?usp=share_link)\
*__Figure 18__. First Frame of Sequence 017*

Raw Sequence Size:  9.82 GB\
Source: [HERE](https://drive.google.com/drive/folders/17sLpoKqUAQhiLmESB4niZ0b9vrQ51YHG?usp=share_link)

<br>

*__Table 18__. Description of encoded videos using sequence 017 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">017_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   4.97</td><td>   3.97</td><td>1</td><td>299</td><td>0</td><td>67.31</td><td>38.93</td><td>40.24</td><td>  0.953</td><td>30.95</td><td>42.52</td><td>43.32</td><td>58.66</td><td> 3.70</td><td> 3.11</td><td>  0.955</td><td>  0.960</td><td>  0.971</td></tr>
<tr><td align="left">017_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  11.46</td><td>   9.16</td><td>1</td><td>299</td><td>0</td><td>65.74</td><td>38.42</td><td>40.73</td><td>  0.952</td><td>30.94</td><td>41.63</td><td>42.69</td><td>59.07</td><td> 4.57</td><td> 3.59</td><td>  0.957</td><td>  0.951</td><td>  0.967</td></tr>
<tr><td align="left">017_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.43</td><td>   1.94</td><td>1</td><td>299</td><td>0</td><td>69.74</td><td>40.11</td><td>38.72</td><td>  0.952</td><td>31.10</td><td>44.52</td><td>44.70</td><td>56.91</td><td> 2.37</td><td> 2.30</td><td>  0.949</td><td>  0.974</td><td>  0.977</td></tr>
<tr><td align="left">017_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  26.48</td><td>  21.16</td><td>1</td><td>299</td><td>0</td><td>63.45</td><td>38.18</td><td>41.05</td><td>  0.952</td><td>30.92</td><td>41.26</td><td>42.36</td><td>59.37</td><td> 4.97</td><td> 3.87</td><td>  0.963</td><td>  0.951</td><td>  0.967</td></tr>
<tr><td align="left">017_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.04</td><td>   2.43</td><td>1</td><td>299</td><td>0</td><td>68.12</td><td>39.52</td><td>39.67</td><td>  0.952</td><td>30.99</td><td>43.50</td><td>44.07</td><td>58.12</td><td> 2.97</td><td> 2.63</td><td>  0.951</td><td>  0.967</td><td>  0.974</td></tr>
<tr><td align="left">017_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  99.39</td><td>  79.43</td><td>1</td><td>299</td><td>0</td><td>60.38</td><td>37.96</td><td>41.37</td><td>  0.951</td><td>30.91</td><td>40.95</td><td>42.03</td><td>59.67</td><td> 5.36</td><td> 4.20</td><td>  0.975</td><td>  0.962</td><td>  0.974</td></tr>
<tr><td align="left">017_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  14.05</td><td>  11.23</td><td>2</td><td>76</td><td>222</td><td>66.92</td><td>38.34</td><td>40.70</td><td>  0.952</td><td>30.92</td><td>41.63</td><td>42.48</td><td>58.98</td><td> 4.53</td><td> 3.75</td><td>  0.951</td><td>  0.951</td><td>  0.965</td></tr>
<tr><td align="left">017_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  28.26</td><td>  22.58</td><td>2</td><td>76</td><td>222</td><td>65.51</td><td>38.19</td><td>41.04</td><td>  0.951</td><td>30.91</td><td>41.30</td><td>42.35</td><td>59.38</td><td> 4.90</td><td> 3.87</td><td>  0.955</td><td>  0.947</td><td>  0.963</td></tr>
<tr><td align="left">017_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.42</td><td>   5.13</td><td>2</td><td>76</td><td>222</td><td>69.41</td><td>39.49</td><td>39.15</td><td>  0.951</td><td>31.06</td><td>43.45</td><td>43.94</td><td>57.29</td><td> 3.01</td><td> 2.71</td><td>  0.946</td><td>  0.965</td><td>  0.972</td></tr>
<tr><td align="left">017_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  63.38</td><td>  50.66</td><td>2</td><td>76</td><td>222</td><td>63.48</td><td>37.98</td><td>41.28</td><td>  0.952</td><td>30.90</td><td>41.01</td><td>42.04</td><td>59.57</td><td> 5.25</td><td> 4.15</td><td>  0.961</td><td>  0.947</td><td>  0.964</td></tr>
<tr><td align="left">017_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   9.07</td><td>   7.25</td><td>2</td><td>76</td><td>222</td><td>67.69</td><td>38.92</td><td>40.11</td><td>  0.951</td><td>30.96</td><td>42.48</td><td>43.31</td><td>58.46</td><td> 3.74</td><td> 3.11</td><td>  0.947</td><td>  0.957</td><td>  0.968</td></tr>
<tr><td align="left">017_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 206.04</td><td> 164.67</td><td>3</td><td>78</td><td>219</td><td>60.30</td><td>37.83</td><td>41.67</td><td>  0.951</td><td>30.94</td><td>40.73</td><td>41.81</td><td>59.95</td><td> 5.74</td><td> 4.47</td><td>  0.972</td><td>  0.958</td><td>  0.971</td></tr>
<tr><td align="left">017_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.17</td><td>  10.53</td><td>2</td><td>76</td><td>222</td><td>66.75</td><td>38.51</td><td>40.64</td><td>  0.952</td><td>30.93</td><td>41.85</td><td>42.76</td><td>58.99</td><td> 4.31</td><td> 3.53</td><td>  0.951</td><td>  0.952</td><td>  0.966</td></tr>
<tr><td align="left">017_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.26</td><td>  20.98</td><td>2</td><td>76</td><td>222</td><td>61.38</td><td>38.21</td><td>41.72</td><td>  0.950</td><td>30.76</td><td>41.39</td><td>42.47</td><td>60.44</td><td> 4.81</td><td> 3.77</td><td>  0.952</td><td>  0.948</td><td>  0.964</td></tr>
<tr><td align="left">017_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.48</td><td>   5.18</td><td>2</td><td>76</td><td>222</td><td>69.34</td><td>39.60</td><td>39.14</td><td>  0.951</td><td>31.06</td><td>43.63</td><td>44.11</td><td>57.33</td><td> 2.90</td><td> 2.61</td><td>  0.945</td><td>  0.967</td><td>  0.973</td></tr>
<tr><td align="left">017_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.25</td><td>  47.36</td><td>2</td><td>76</td><td>222</td><td>63.24</td><td>38.05</td><td>41.23</td><td>  0.952</td><td>30.91</td><td>41.09</td><td>42.16</td><td>59.55</td><td> 5.16</td><td> 4.05</td><td>  0.961</td><td>  0.948</td><td>  0.964</td></tr>
<tr><td align="left">017_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.89</td><td>   7.11</td><td>2</td><td>76</td><td>222</td><td>61.11</td><td>38.87</td><td>42.36</td><td>  0.946</td><td>30.58</td><td>42.60</td><td>43.42</td><td>61.86</td><td> 3.64</td><td> 3.03</td><td>  0.938</td><td>  0.959</td><td>  0.970</td></tr>
<tr><td align="left">017_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 198.57</td><td> 158.69</td><td>2</td><td>76</td><td>222</td><td>61.11</td><td>38.87</td><td>41.67</td><td>  0.946</td><td>30.58</td><td>42.60</td><td>43.42</td><td>59.99</td><td> 5.68</td><td> 4.40</td><td>  0.973</td><td>  0.959</td><td>  0.972</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 018
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/018_480p.png)](https://drive.google.com/drive/folders/1gpKwiGLZ03IV0PIWQlB5eEfxo-rsNlKN?usp=sharing)\
*__Figure 19__. First Frame of Sequence 018*

Raw Sequence Size:  9.73 GB\
Source: [HERE](https://drive.google.com/drive/folders/1gpKwiGLZ03IV0PIWQlB5eEfxo-rsNlKN?usp=sharing)

<br>

*__Table 19__. Description of encoded videos using sequence 018 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">018_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.46</td><td>   4.36</td><td>1</td><td>299</td><td>0</td><td> 3.53</td><td>43.35</td><td>147.74</td><td>  0.719</td><td>25.56</td><td>51.96</td><td>52.52</td><td>221.41</td><td> 0.43</td><td> 0.37</td><td>  0.747</td><td>  0.995</td><td>  0.995</td></tr>
<tr><td align="left">018_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.39</td><td>   8.30</td><td>1</td><td>299</td><td>0</td><td> 2.85</td><td>42.68</td><td>148.51</td><td>  0.721</td><td>25.54</td><td>50.47</td><td>52.02</td><td>222.54</td><td> 0.61</td><td> 0.42</td><td>  0.770</td><td>  0.993</td><td>  0.994</td></tr>
<tr><td align="left">018_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.39</td><td>   1.91</td><td>1</td><td>299</td><td>0</td><td> 8.69</td><td>43.39</td><td>140.17</td><td>  0.716</td><td>25.88</td><td>51.59</td><td>52.70</td><td>210.05</td><td> 0.47</td><td> 0.35</td><td>  0.702</td><td>  0.993</td><td>  0.995</td></tr>
<tr><td align="left">018_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  20.69</td><td>  16.53</td><td>1</td><td>299</td><td>0</td><td> 2.23</td><td>42.29</td><td>148.84</td><td>  0.721</td><td>25.53</td><td>50.20</td><td>51.13</td><td>222.97</td><td> 0.64</td><td> 0.52</td><td>  0.807</td><td>  0.993</td><td>  0.993</td></tr>
<tr><td align="left">018_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.58</td><td>   2.86</td><td>1</td><td>299</td><td>0</td><td> 5.32</td><td>43.09</td><td>145.07</td><td>  0.720</td><td>25.67</td><td>51.93</td><td>51.67</td><td>217.44</td><td> 0.43</td><td> 0.45</td><td>  0.720</td><td>  0.994</td><td>  0.993</td></tr>
<tr><td align="left">018_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  78.01</td><td>  62.35</td><td>1</td><td>299</td><td>0</td><td> 2.18</td><td>41.99</td><td>149.04</td><td>  0.721</td><td>25.52</td><td>49.98</td><td>50.47</td><td>223.23</td><td> 0.67</td><td> 0.60</td><td>  0.873</td><td>  0.995</td><td>  0.993</td></tr>
<tr><td align="left">018_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  11.53</td><td>   9.22</td><td>2</td><td>76</td><td>222</td><td> 3.47</td><td>42.07</td><td>147.41</td><td>  0.720</td><td>25.54</td><td>48.45</td><td>52.22</td><td>220.78</td><td> 0.94</td><td> 0.40</td><td>  0.746</td><td>  0.994</td><td>  0.995</td></tr>
<tr><td align="left">018_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  21.83</td><td>  17.45</td><td>2</td><td>76</td><td>222</td><td> 2.83</td><td>41.45</td><td>148.46</td><td>  0.721</td><td>25.52</td><td>50.46</td><td>48.36</td><td>222.33</td><td> 0.60</td><td> 0.95</td><td>  0.769</td><td>  0.993</td><td>  0.994</td></tr>
<tr><td align="left">018_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   4.49</td><td>   3.59</td><td>2</td><td>76</td><td>222</td><td> 8.65</td><td>42.32</td><td>139.85</td><td>  0.716</td><td>25.86</td><td>51.37</td><td>49.72</td><td>209.48</td><td> 0.49</td><td> 0.69</td><td>  0.702</td><td>  0.994</td><td>  0.995</td></tr>
<tr><td align="left">018_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  48.77</td><td>  38.98</td><td>2</td><td>76</td><td>222</td><td> 2.23</td><td>41.88</td><td>149.00</td><td>  0.721</td><td>25.51</td><td>49.05</td><td>51.08</td><td>223.16</td><td> 0.82</td><td> 0.52</td><td>  0.805</td><td>  0.993</td><td>  0.993</td></tr>
<tr><td align="left">018_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   7.30</td><td>   5.83</td><td>2</td><td>76</td><td>222</td><td> 5.26</td><td>41.58</td><td>144.74</td><td>  0.720</td><td>25.65</td><td>49.41</td><td>49.68</td><td>216.80</td><td> 0.75</td><td> 0.70</td><td>  0.720</td><td>  0.994</td><td>  0.994</td></tr>
<tr><td align="left">018_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 193.62</td><td> 154.74</td><td>2</td><td>77</td><td>221</td><td> 2.21</td><td>41.90</td><td>149.13</td><td>  0.721</td><td>25.57</td><td>49.78</td><td>50.37</td><td>223.37</td><td> 0.71</td><td> 0.61</td><td>  0.870</td><td>  0.994</td><td>  0.993</td></tr>
<tr><td align="left">018_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.29</td><td>   9.82</td><td>2</td><td>76</td><td>222</td><td> 3.48</td><td>42.23</td><td>147.29</td><td>  0.720</td><td>25.55</td><td>48.81</td><td>52.32</td><td>220.63</td><td> 0.86</td><td> 0.39</td><td>  0.748</td><td>  0.994</td><td>  0.995</td></tr>
<tr><td align="left">018_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  24.02</td><td>  19.20</td><td>2</td><td>76</td><td>222</td><td> 2.69</td><td>41.36</td><td>148.14</td><td>  0.721</td><td>25.48</td><td>50.40</td><td>48.21</td><td>221.81</td><td> 0.61</td><td> 0.98</td><td>  0.771</td><td>  0.993</td><td>  0.994</td></tr>
<tr><td align="left">018_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   3.97</td><td>   3.17</td><td>2</td><td>76</td><td>222</td><td> 8.65</td><td>42.27</td><td>139.91</td><td>  0.717</td><td>25.86</td><td>51.39</td><td>49.57</td><td>209.57</td><td> 0.49</td><td> 0.72</td><td>  0.703</td><td>  0.993</td><td>  0.995</td></tr>
<tr><td align="left">018_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  54.57</td><td>  43.61</td><td>2</td><td>76</td><td>222</td><td> 2.21</td><td>41.94</td><td>148.76</td><td>  0.721</td><td>25.51</td><td>49.28</td><td>51.02</td><td>222.82</td><td> 0.78</td><td> 0.53</td><td>  0.807</td><td>  0.993</td><td>  0.993</td></tr>
<tr><td align="left">018_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   6.98</td><td>   5.58</td><td>2</td><td>76</td><td>222</td><td> 5.05</td><td>41.62</td><td>144.42</td><td>  0.721</td><td>25.58</td><td>49.69</td><td>49.59</td><td>216.27</td><td> 0.70</td><td> 0.72</td><td>  0.721</td><td>  0.993</td><td>  0.994</td></tr>
<tr><td align="left">018_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 192.40</td><td> 153.76</td><td>2</td><td>76</td><td>222</td><td> 5.05</td><td>41.62</td><td>149.01</td><td>  0.721</td><td>25.58</td><td>49.69</td><td>49.59</td><td>223.18</td><td> 0.70</td><td> 0.64</td><td>  0.873</td><td>  0.994</td><td>  0.992</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 019
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/019_480p.png)](https://drive.google.com/drive/folders/1cKPTbkDro_DCzgZKtirpv59T86NO0ZDv?usp=share_link)\
*__Figure 20__. First Frame of Sequence 019*

Raw Sequence Size: 15.04 GB\
Source: [HERE](https://drive.google.com/drive/folders/1cKPTbkDro_DCzgZKtirpv59T86NO0ZDv?usp=share_link)

<br>

*__Table 20__. Description of encoded videos using sequence 019 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">019_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.57</td><td>   4.45</td><td>1</td><td>299</td><td>0</td><td>22.77</td><td>35.25</td><td>90.84</td><td>  0.844</td><td>27.67</td><td>38.51</td><td>39.57</td><td>131.51</td><td>10.77</td><td> 8.19</td><td>  0.789</td><td>  0.928</td><td>  0.945</td></tr>
<tr><td align="left">019_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.31</td><td>   8.24</td><td>1</td><td>299</td><td>0</td><td>19.43</td><td>34.90</td><td>93.77</td><td>  0.853</td><td>27.53</td><td>38.07</td><td>39.10</td><td>135.46</td><td>11.80</td><td> 9.06</td><td>  0.794</td><td>  0.924</td><td>  0.941</td></tr>
<tr><td align="left">019_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.27</td><td>   1.81</td><td>1</td><td>299</td><td>0</td><td>37.30</td><td>36.43</td><td>77.16</td><td>  0.850</td><td>28.46</td><td>39.93</td><td>40.90</td><td>112.26</td><td> 7.84</td><td> 6.08</td><td>  0.809</td><td>  0.944</td><td>  0.956</td></tr>
<tr><td align="left">019_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  21.14</td><td>  16.90</td><td>1</td><td>299</td><td>0</td><td>14.73</td><td>34.57</td><td>95.96</td><td>  0.846</td><td>27.42</td><td>37.62</td><td>38.67</td><td>138.29</td><td>12.81</td><td> 9.82</td><td>  0.811</td><td>  0.923</td><td>  0.939</td></tr>
<tr><td align="left">019_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.59</td><td>   2.87</td><td>1</td><td>299</td><td>0</td><td>30.01</td><td>35.79</td><td>85.07</td><td>  0.851</td><td>27.99</td><td>39.21</td><td>40.17</td><td>123.53</td><td> 9.26</td><td> 7.19</td><td>  0.793</td><td>  0.935</td><td>  0.950</td></tr>
<tr><td align="left">019_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  81.13</td><td>  64.84</td><td>1</td><td>299</td><td>0</td><td> 8.64</td><td>34.15</td><td>97.23</td><td>  0.851</td><td>27.36</td><td>37.03</td><td>38.06</td><td>139.50</td><td>14.31</td><td>11.09</td><td>  0.857</td><td>  0.930</td><td>  0.942</td></tr>
<tr><td align="left">019_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.75</td><td>  10.19</td><td>2</td><td>76</td><td>222</td><td>22.45</td><td>35.19</td><td>90.40</td><td>  0.845</td><td>27.67</td><td>38.40</td><td>39.50</td><td>130.93</td><td>10.65</td><td> 8.06</td><td>  0.789</td><td>  0.930</td><td>  0.946</td></tr>
<tr><td align="left">019_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.01</td><td>  20.78</td><td>2</td><td>76</td><td>222</td><td>19.15</td><td>34.90</td><td>93.44</td><td>  0.853</td><td>27.52</td><td>38.08</td><td>39.10</td><td>135.06</td><td>11.54</td><td> 8.90</td><td>  0.794</td><td>  0.926</td><td>  0.942</td></tr>
<tr><td align="left">019_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   5.55</td><td>   4.43</td><td>2</td><td>76</td><td>222</td><td>36.91</td><td>36.25</td><td>77.12</td><td>  0.849</td><td>28.46</td><td>39.68</td><td>40.62</td><td>112.12</td><td> 8.01</td><td> 6.26</td><td>  0.808</td><td>  0.942</td><td>  0.954</td></tr>
<tr><td align="left">019_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  59.04</td><td>  47.19</td><td>2</td><td>76</td><td>222</td><td>14.58</td><td>34.51</td><td>95.98</td><td>  0.846</td><td>27.40</td><td>37.54</td><td>38.60</td><td>138.29</td><td>12.85</td><td> 9.85</td><td>  0.810</td><td>  0.923</td><td>  0.938</td></tr>
<tr><td align="left">019_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.40</td><td>   6.71</td><td>2</td><td>76</td><td>222</td><td>29.52</td><td>35.73</td><td>84.69</td><td>  0.851</td><td>28.00</td><td>39.10</td><td>40.09</td><td>122.97</td><td> 9.23</td><td> 7.14</td><td>  0.793</td><td>  0.935</td><td>  0.950</td></tr>
<tr><td align="left">019_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 209.55</td><td> 167.48</td><td>2</td><td>76</td><td>222</td><td> 8.51</td><td>34.22</td><td>97.44</td><td>  0.851</td><td>27.40</td><td>37.14</td><td>38.13</td><td>139.82</td><td>14.24</td><td>11.09</td><td>  0.855</td><td>  0.930</td><td>  0.941</td></tr>
<tr><td align="left">019_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.81</td><td>  10.24</td><td>2</td><td>76</td><td>222</td><td>22.48</td><td>35.16</td><td>90.46</td><td>  0.845</td><td>27.67</td><td>38.37</td><td>39.45</td><td>130.93</td><td>10.80</td><td> 8.22</td><td>  0.790</td><td>  0.928</td><td>  0.944</td></tr>
<tr><td align="left">019_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  25.80</td><td>  20.62</td><td>2</td><td>76</td><td>222</td><td>19.53</td><td>34.83</td><td>93.70</td><td>  0.853</td><td>27.42</td><td>38.03</td><td>39.04</td><td>135.34</td><td>11.76</td><td> 9.07</td><td>  0.794</td><td>  0.924</td><td>  0.940</td></tr>
<tr><td align="left">019_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   5.50</td><td>   4.40</td><td>2</td><td>76</td><td>222</td><td>36.93</td><td>36.25</td><td>77.12</td><td>  0.850</td><td>28.46</td><td>39.68</td><td>40.61</td><td>112.09</td><td> 8.06</td><td> 6.31</td><td>  0.809</td><td>  0.941</td><td>  0.954</td></tr>
<tr><td align="left">019_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.68</td><td>  46.90</td><td>2</td><td>76</td><td>222</td><td>14.59</td><td>34.49</td><td>95.87</td><td>  0.846</td><td>27.41</td><td>37.50</td><td>38.55</td><td>138.07</td><td>12.98</td><td> 9.99</td><td>  0.811</td><td>  0.922</td><td>  0.937</td></tr>
<tr><td align="left">019_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.30</td><td>   6.63</td><td>2</td><td>76</td><td>222</td><td>28.49</td><td>35.61</td><td>86.60</td><td>  0.848</td><td>27.72</td><td>39.06</td><td>40.04</td><td>125.74</td><td> 9.39</td><td> 7.28</td><td>  0.787</td><td>  0.934</td><td>  0.949</td></tr>
<tr><td align="left">019_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 198.21</td><td> 158.41</td><td>2</td><td>76</td><td>222</td><td> 8.58</td><td>34.08</td><td>97.33</td><td>  0.851</td><td>27.35</td><td>36.96</td><td>37.94</td><td>139.55</td><td>14.47</td><td>11.31</td><td>  0.857</td><td>  0.928</td><td>  0.939</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 020
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/020_480p.png)](https://drive.google.com/drive/folders/1Ss7JO2Do-UcA1uGSFQo-qp_InNCCihuu?usp=share_link)\
*__Figure 21__. First Frame of Sequence 020*

Raw Sequence Size:  6.48 GB\
Source: [HERE](https://drive.google.com/drive/folders/1Ss7JO2Do-UcA1uGSFQo-qp_InNCCihuu?usp=share_link)

<br>

*__Table 21__. Description of encoded videos using sequence 020 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">020_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.31</td><td>   4.24</td><td>1</td><td>299</td><td>0</td><td>73.82</td><td>44.28</td><td>18.59</td><td>  0.970</td><td>34.22</td><td>49.52</td><td>49.11</td><td>27.48</td><td> 0.76</td><td> 0.83</td><td>  0.970</td><td>  0.994</td><td>  0.993</td></tr>
<tr><td align="left">020_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.13</td><td>   7.30</td><td>1</td><td>299</td><td>0</td><td>70.52</td><td>44.20</td><td>18.75</td><td>  0.970</td><td>34.18</td><td>49.45</td><td>48.97</td><td>27.72</td><td> 0.77</td><td> 0.86</td><td>  0.973</td><td>  0.994</td><td>  0.993</td></tr>
<tr><td align="left">020_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.48</td><td>   1.98</td><td>1</td><td>299</td><td>0</td><td>80.24</td><td>45.21</td><td>17.42</td><td>  0.970</td><td>34.50</td><td>50.66</td><td>50.48</td><td>25.83</td><td> 0.59</td><td> 0.62</td><td>  0.968</td><td>  0.994</td><td>  0.993</td></tr>
<tr><td align="left">020_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  19.64</td><td>  15.70</td><td>1</td><td>299</td><td>0</td><td>65.74</td><td>44.24</td><td>18.91</td><td>  0.971</td><td>34.15</td><td>49.42</td><td>49.15</td><td>27.96</td><td> 0.78</td><td> 0.83</td><td>  0.976</td><td>  0.995</td><td>  0.994</td></tr>
<tr><td align="left">020_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.25</td><td>   2.59</td><td>1</td><td>299</td><td>0</td><td>77.60</td><td>44.70</td><td>18.15</td><td>  0.970</td><td>34.32</td><td>50.12</td><td>49.66</td><td>26.89</td><td> 0.66</td><td> 0.73</td><td>  0.968</td><td>  0.994</td><td>  0.993</td></tr>
<tr><td align="left">020_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  82.10</td><td>  65.62</td><td>1</td><td>299</td><td>0</td><td>59.28</td><td>44.07</td><td>19.07</td><td>  0.970</td><td>34.13</td><td>49.30</td><td>48.77</td><td>28.18</td><td> 0.80</td><td> 0.90</td><td>  0.983</td><td>  0.996</td><td>  0.995</td></tr>
<tr><td align="left">020_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.08</td><td>   9.66</td><td>2</td><td>76</td><td>222</td><td>73.40</td><td>43.47</td><td>18.86</td><td>  0.970</td><td>34.14</td><td>48.36</td><td>47.93</td><td>27.78</td><td> 0.97</td><td> 1.07</td><td>  0.968</td><td>  0.992</td><td>  0.991</td></tr>
<tr><td align="left">020_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  22.52</td><td>  17.99</td><td>2</td><td>76</td><td>222</td><td>70.24</td><td>43.59</td><td>18.96</td><td>  0.970</td><td>34.12</td><td>48.59</td><td>48.07</td><td>27.95</td><td> 0.92</td><td> 1.04</td><td>  0.971</td><td>  0.992</td><td>  0.991</td></tr>
<tr><td align="left">020_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   3.70</td><td>   2.96</td><td>2</td><td>76</td><td>222</td><td>79.72</td><td>43.94</td><td>17.70</td><td>  0.969</td><td>34.41</td><td>48.79</td><td>48.63</td><td>26.10</td><td> 0.87</td><td> 0.91</td><td>  0.965</td><td>  0.991</td><td>  0.991</td></tr>
<tr><td align="left">020_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  50.18</td><td>  40.11</td><td>2</td><td>76</td><td>222</td><td>65.68</td><td>43.58</td><td>19.14</td><td>  0.970</td><td>34.09</td><td>48.37</td><td>48.29</td><td>28.21</td><td> 0.97</td><td> 1.00</td><td>  0.975</td><td>  0.993</td><td>  0.992</td></tr>
<tr><td align="left">020_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   7.14</td><td>   5.70</td><td>2</td><td>76</td><td>222</td><td>77.10</td><td>43.68</td><td>18.45</td><td>  0.970</td><td>34.22</td><td>48.71</td><td>48.12</td><td>27.21</td><td> 0.89</td><td> 1.02</td><td>  0.966</td><td>  0.991</td><td>  0.991</td></tr>
<tr><td align="left">020_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 192.73</td><td> 154.03</td><td>2</td><td>76</td><td>222</td><td>59.28</td><td>43.80</td><td>19.17</td><td>  0.970</td><td>34.14</td><td>48.94</td><td>48.32</td><td>28.29</td><td> 0.87</td><td> 1.00</td><td>  0.982</td><td>  0.995</td><td>  0.994</td></tr>
<tr><td align="left">020_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.70</td><td>  10.15</td><td>2</td><td>76</td><td>222</td><td>73.36</td><td>43.57</td><td>18.79</td><td>  0.970</td><td>34.14</td><td>48.53</td><td>48.05</td><td>27.69</td><td> 0.93</td><td> 1.04</td><td>  0.969</td><td>  0.992</td><td>  0.991</td></tr>
<tr><td align="left">020_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.28</td><td>  21.00</td><td>2</td><td>76</td><td>222</td><td>66.38</td><td>43.60</td><td>19.82</td><td>  0.969</td><td>33.80</td><td>48.76</td><td>48.25</td><td>29.26</td><td> 0.89</td><td> 1.00</td><td>  0.968</td><td>  0.993</td><td>  0.992</td></tr>
<tr><td align="left">020_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   4.10</td><td>   3.28</td><td>2</td><td>76</td><td>222</td><td>79.70</td><td>43.91</td><td>17.69</td><td>  0.969</td><td>34.41</td><td>48.77</td><td>48.54</td><td>26.09</td><td> 0.88</td><td> 0.93</td><td>  0.965</td><td>  0.991</td><td>  0.991</td></tr>
<tr><td align="left">020_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.66</td><td>  47.68</td><td>2</td><td>76</td><td>222</td><td>65.59</td><td>43.77</td><td>19.06</td><td>  0.970</td><td>34.10</td><td>48.68</td><td>48.52</td><td>28.13</td><td> 0.91</td><td> 0.94</td><td>  0.975</td><td>  0.993</td><td>  0.993</td></tr>
<tr><td align="left">020_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.35</td><td>   5.88</td><td>2</td><td>76</td><td>222</td><td>70.31</td><td>43.42</td><td>21.38</td><td>  0.965</td><td>33.37</td><td>48.84</td><td>48.06</td><td>31.59</td><td> 0.87</td><td> 1.04</td><td>  0.956</td><td>  0.991</td><td>  0.991</td></tr>
<tr><td align="left">020_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 197.93</td><td> 158.18</td><td>2</td><td>76</td><td>222</td><td>59.24</td><td>43.73</td><td>19.16</td><td>  0.970</td><td>34.11</td><td>48.83</td><td>48.26</td><td>28.27</td><td> 0.88</td><td> 1.00</td><td>  0.983</td><td>  0.995</td><td>  0.994</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 021
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/021_480p.png)](https://drive.google.com/drive/folders/1GN4c0wgolAYQr51oFJvyxQR2iAQCgWS7?usp=share_link)\
*__Figure 22__. First Frame of Sequence 021*

Raw Sequence Size:  8.72 GB\
Source: [HERE](https://drive.google.com/drive/folders/1GN4c0wgolAYQr51oFJvyxQR2iAQCgWS7?usp=share_link)

<br>

*__Table 22__. Description of encoded videos using sequence 021 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">021_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.10</td><td>   4.07</td><td>1</td><td>299</td><td>0</td><td> 8.72</td><td>34.30</td><td>457.92</td><td>  0.425</td><td>20.65</td><td>41.29</td><td>40.95</td><td>684.10</td><td> 5.36</td><td> 5.76</td><td>  0.544</td><td>  0.963</td><td>  0.960</td></tr>
<tr><td align="left">021_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.12</td><td>   7.29</td><td>1</td><td>299</td><td>0</td><td> 8.19</td><td>34.24</td><td>458.15</td><td>  0.420</td><td>20.67</td><td>41.29</td><td>40.76</td><td>684.47</td><td> 5.35</td><td> 6.02</td><td>  0.605</td><td>  0.968</td><td>  0.965</td></tr>
<tr><td align="left">021_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.31</td><td>   1.84</td><td>1</td><td>299</td><td>0</td><td> 9.88</td><td>34.55</td><td>451.79</td><td>  0.412</td><td>20.72</td><td>41.63</td><td>41.30</td><td>675.07</td><td> 5.05</td><td> 5.39</td><td>  0.418</td><td>  0.950</td><td>  0.946</td></tr>
<tr><td align="left">021_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  18.44</td><td>  14.74</td><td>1</td><td>299</td><td>0</td><td> 7.23</td><td>34.25</td><td>457.88</td><td>  0.427</td><td>20.69</td><td>41.25</td><td>40.81</td><td>683.97</td><td> 5.41</td><td> 5.97</td><td>  0.695</td><td>  0.977</td><td>  0.975</td></tr>
<tr><td align="left">021_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.48</td><td>   2.78</td><td>1</td><td>299</td><td>0</td><td> 9.41</td><td>34.38</td><td>456.26</td><td>  0.416</td><td>20.66</td><td>41.70</td><td>40.79</td><td>681.83</td><td> 4.87</td><td> 6.04</td><td>  0.471</td><td>  0.957</td><td>  0.950</td></tr>
<tr><td align="left">021_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  67.22</td><td>  53.72</td><td>1</td><td>299</td><td>0</td><td> 5.56</td><td>34.19</td><td>457.73</td><td>  0.423</td><td>20.72</td><td>41.23</td><td>40.60</td><td>683.67</td><td> 5.44</td><td> 6.26</td><td>  0.835</td><td>  0.988</td><td>  0.986</td></tr>
<tr><td align="left">021_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.05</td><td>  10.43</td><td>2</td><td>78</td><td>220</td><td> 8.71</td><td>34.20</td><td>457.87</td><td>  0.425</td><td>20.65</td><td>41.20</td><td>40.76</td><td>683.99</td><td> 5.36</td><td> 5.92</td><td>  0.543</td><td>  0.965</td><td>  0.962</td></tr>
<tr><td align="left">021_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  25.59</td><td>  20.45</td><td>2</td><td>80</td><td>218</td><td> 8.21</td><td>34.24</td><td>458.17</td><td>  0.420</td><td>20.67</td><td>41.35</td><td>40.70</td><td>684.51</td><td> 5.24</td><td> 6.05</td><td>  0.602</td><td>  0.969</td><td>  0.966</td></tr>
<tr><td align="left">021_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.14</td><td>   4.91</td><td>2</td><td>76</td><td>222</td><td> 9.80</td><td>34.69</td><td>450.46</td><td>  0.413</td><td>20.74</td><td>41.93</td><td>41.41</td><td>673.23</td><td> 4.64</td><td> 5.19</td><td>  0.418</td><td>  0.955</td><td>  0.950</td></tr>
<tr><td align="left">021_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  57.87</td><td>  46.25</td><td>2</td><td>85</td><td>213</td><td> 7.28</td><td>34.12</td><td>458.58</td><td>  0.426</td><td>20.68</td><td>41.07</td><td>40.61</td><td>684.94</td><td> 5.54</td><td> 6.19</td><td>  0.691</td><td>  0.976</td><td>  0.973</td></tr>
<tr><td align="left">021_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.43</td><td>   6.74</td><td>2</td><td>76</td><td>222</td><td> 9.38</td><td>34.49</td><td>455.89</td><td>  0.417</td><td>20.66</td><td>41.81</td><td>41.00</td><td>681.39</td><td> 4.72</td><td> 5.69</td><td>  0.470</td><td>  0.961</td><td>  0.955</td></tr>
<tr><td align="left">021_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 188.07</td><td> 150.31</td><td>4</td><td>78</td><td>218</td><td> 5.63</td><td>34.13</td><td>458.22</td><td>  0.423</td><td>20.76</td><td>41.12</td><td>40.50</td><td>684.32</td><td> 5.61</td><td> 6.45</td><td>  0.832</td><td>  0.986</td><td>  0.984</td></tr>
<tr><td align="left">021_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.79</td><td>  10.22</td><td>2</td><td>76</td><td>222</td><td> 8.66</td><td>34.24</td><td>457.11</td><td>  0.426</td><td>20.68</td><td>41.26</td><td>40.78</td><td>682.85</td><td> 5.32</td><td> 5.93</td><td>  0.545</td><td>  0.964</td><td>  0.960</td></tr>
<tr><td align="left">021_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.03</td><td>  20.81</td><td>2</td><td>76</td><td>222</td><td> 8.12</td><td>34.17</td><td>457.77</td><td>  0.420</td><td>20.61</td><td>41.26</td><td>40.63</td><td>683.78</td><td> 5.35</td><td> 6.16</td><td>  0.605</td><td>  0.968</td><td>  0.964</td></tr>
<tr><td align="left">021_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.30</td><td>   5.04</td><td>2</td><td>76</td><td>222</td><td> 9.81</td><td>34.57</td><td>450.31</td><td>  0.414</td><td>20.75</td><td>41.75</td><td>41.19</td><td>672.89</td><td> 4.84</td><td> 5.45</td><td>  0.419</td><td>  0.952</td><td>  0.947</td></tr>
<tr><td align="left">021_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.69</td><td>  46.91</td><td>2</td><td>76</td><td>222</td><td> 7.24</td><td>34.15</td><td>458.07</td><td>  0.426</td><td>20.70</td><td>41.13</td><td>40.61</td><td>684.17</td><td> 5.49</td><td> 6.20</td><td>  0.694</td><td>  0.975</td><td>  0.972</td></tr>
<tr><td align="left">021_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.30</td><td>   6.63</td><td>2</td><td>76</td><td>222</td><td> 9.22</td><td>34.36</td><td>455.82</td><td>  0.416</td><td>20.58</td><td>41.70</td><td>40.81</td><td>681.03</td><td> 4.86</td><td> 5.94</td><td>  0.472</td><td>  0.958</td><td>  0.952</td></tr>
<tr><td align="left">021_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 197.46</td><td> 157.81</td><td>2</td><td>76</td><td>222</td><td> 5.60</td><td>34.12</td><td>458.16</td><td>  0.423</td><td>20.72</td><td>41.16</td><td>40.48</td><td>684.26</td><td> 5.49</td><td> 6.40</td><td>  0.833</td><td>  0.986</td><td>  0.984</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 022
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/022_480p.png)](https://drive.google.com/drive/folders/1yKmK7s2gx4roQmGLwitOnJn0Ouq4TCaA?usp=share_link)\
*__Figure 23__. First Frame of Sequence 022*

Raw Sequence Size:  5.13 GB\
Source: [HERE](https://drive.google.com/drive/folders/1yKmK7s2gx4roQmGLwitOnJn0Ouq4TCaA?usp=share_link)

<br>

*__Table 23__. Description of encoded videos using sequence 022 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">022_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.17</td><td>   4.13</td><td>1</td><td>299</td><td>0</td><td> 2.92</td><td>32.46</td><td>753.16</td><td>  0.692</td><td>20.18</td><td>38.67</td><td>38.52</td><td>1123.93</td><td>11.42</td><td>11.81</td><td>  0.820</td><td>  0.982</td><td>  0.980</td></tr>
<tr><td align="left">022_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.78</td><td>   7.82</td><td>1</td><td>299</td><td>0</td><td> 3.06</td><td>32.34</td><td>753.35</td><td>  0.675</td><td>20.20</td><td>38.55</td><td>38.27</td><td>1124.10</td><td>11.79</td><td>12.49</td><td>  0.850</td><td>  0.985</td><td>  0.983</td></tr>
<tr><td align="left">022_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.30</td><td>   1.84</td><td>1</td><td>299</td><td>0</td><td> 4.33</td><td>32.40</td><td>754.37</td><td>  0.674</td><td>20.17</td><td>38.69</td><td>38.35</td><td>1125.54</td><td>11.48</td><td>12.56</td><td>  0.717</td><td>  0.966</td><td>  0.963</td></tr>
<tr><td align="left">022_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  20.06</td><td>  16.04</td><td>1</td><td>299</td><td>0</td><td> 4.83</td><td>32.44</td><td>753.29</td><td>  0.692</td><td>20.21</td><td>38.69</td><td>38.43</td><td>1124.04</td><td>11.43</td><td>12.11</td><td>  0.884</td><td>  0.990</td><td>  0.988</td></tr>
<tr><td align="left">022_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.45</td><td>   2.76</td><td>1</td><td>299</td><td>0</td><td> 3.32</td><td>32.42</td><td>753.93</td><td>  0.675</td><td>20.18</td><td>38.84</td><td>38.24</td><td>1125.20</td><td>10.99</td><td>12.90</td><td>  0.771</td><td>  0.975</td><td>  0.971</td></tr>
<tr><td align="left">022_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  74.14</td><td>  59.26</td><td>1</td><td>299</td><td>0</td><td>25.62</td><td>32.34</td><td>753.08</td><td>  0.683</td><td>20.25</td><td>38.53</td><td>38.24</td><td>1123.45</td><td>11.93</td><td>12.72</td><td>  0.924</td><td>  0.994</td><td>  0.993</td></tr>
<tr><td align="left">022_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.14</td><td>  10.50</td><td>2</td><td>78</td><td>220</td><td> 2.88</td><td>32.31</td><td>754.01</td><td>  0.692</td><td>20.17</td><td>38.51</td><td>38.24</td><td>1125.01</td><td>11.42</td><td>12.60</td><td>  0.818</td><td>  0.981</td><td>  0.979</td></tr>
<tr><td align="left">022_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  25.72</td><td>  20.55</td><td>2</td><td>78</td><td>220</td><td> 3.04</td><td>32.29</td><td>752.73</td><td>  0.675</td><td>20.19</td><td>38.48</td><td>38.20</td><td>1123.11</td><td>11.86</td><td>12.62</td><td>  0.849</td><td>  0.985</td><td>  0.982</td></tr>
<tr><td align="left">022_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.05</td><td>   4.83</td><td>2</td><td>76</td><td>222</td><td> 4.30</td><td>32.36</td><td>753.21</td><td>  0.672</td><td>20.17</td><td>38.62</td><td>38.27</td><td>1123.78</td><td>11.55</td><td>12.57</td><td>  0.713</td><td>  0.966</td><td>  0.963</td></tr>
<tr><td align="left">022_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  58.10</td><td>  46.44</td><td>2</td><td>105</td><td>193</td><td> 4.83</td><td>32.33</td><td>753.83</td><td>  0.691</td><td>20.20</td><td>38.56</td><td>38.22</td><td>1124.69</td><td>11.59</td><td>12.65</td><td>  0.883</td><td>  0.989</td><td>  0.986</td></tr>
<tr><td align="left">022_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.53</td><td>   6.81</td><td>2</td><td>77</td><td>221</td><td> 3.32</td><td>32.34</td><td>754.14</td><td>  0.674</td><td>20.17</td><td>38.66</td><td>38.19</td><td>1125.46</td><td>11.35</td><td>12.77</td><td>  0.769</td><td>  0.974</td><td>  0.971</td></tr>
<tr><td align="left">022_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 183.78</td><td> 146.88</td><td>3</td><td>252</td><td>45</td><td>25.69</td><td>32.36</td><td>753.23</td><td>  0.683</td><td>20.29</td><td>38.54</td><td>38.25</td><td>1123.65</td><td>11.97</td><td>12.80</td><td>  0.923</td><td>  0.994</td><td>  0.992</td></tr>
<tr><td align="left">022_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.17</td><td>  10.52</td><td>2</td><td>76</td><td>222</td><td> 2.89</td><td>32.32</td><td>753.59</td><td>  0.692</td><td>20.18</td><td>38.51</td><td>38.27</td><td>1124.38</td><td>11.54</td><td>12.47</td><td>  0.819</td><td>  0.981</td><td>  0.978</td></tr>
<tr><td align="left">022_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.37</td><td>  21.07</td><td>2</td><td>76</td><td>222</td><td> 3.01</td><td>32.28</td><td>752.62</td><td>  0.675</td><td>20.15</td><td>38.48</td><td>38.20</td><td>1122.79</td><td>11.91</td><td>12.62</td><td>  0.849</td><td>  0.985</td><td>  0.982</td></tr>
<tr><td align="left">022_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   5.54</td><td>   4.43</td><td>2</td><td>76</td><td>222</td><td> 4.29</td><td>32.34</td><td>752.55</td><td>  0.673</td><td>20.18</td><td>38.58</td><td>38.26</td><td>1122.75</td><td>11.72</td><td>12.57</td><td>  0.715</td><td>  0.965</td><td>  0.962</td></tr>
<tr><td align="left">022_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  56.80</td><td>  45.40</td><td>2</td><td>76</td><td>222</td><td> 4.84</td><td>32.34</td><td>753.69</td><td>  0.692</td><td>20.21</td><td>38.58</td><td>38.24</td><td>1124.49</td><td>11.62</td><td>12.60</td><td>  0.884</td><td>  0.989</td><td>  0.987</td></tr>
<tr><td align="left">022_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.26</td><td>   6.60</td><td>2</td><td>76</td><td>222</td><td> 3.20</td><td>32.31</td><td>753.81</td><td>  0.674</td><td>20.10</td><td>38.64</td><td>38.19</td><td>1124.65</td><td>11.47</td><td>12.77</td><td>  0.770</td><td>  0.974</td><td>  0.971</td></tr>
<tr><td align="left">022_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 170.60</td><td> 136.34</td><td>2</td><td>76</td><td>222</td><td>25.70</td><td>32.30</td><td>753.27</td><td>  0.683</td><td>20.25</td><td>38.50</td><td>38.16</td><td>1123.71</td><td>11.86</td><td>12.93</td><td>  0.923</td><td>  0.994</td><td>  0.992</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 023
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/023_480p.png)](https://drive.google.com/drive/folders/1_E4fP5i9RE3mQHtGA5vAcDDOQA2LESm1?usp=share_link)\
*__Figure 24__. First Frame of Sequence 023*

Raw Sequence Size:  7.48 GB\
Source: [HERE](https://drive.google.com/drive/folders/1_E4fP5i9RE3mQHtGA5vAcDDOQA2LESm1?usp=share_link)

<br>

*__Table 24__. Description of encoded videos using sequence 023 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">023_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.10</td><td>   4.08</td><td>1</td><td>299</td><td>0</td><td>15.36</td><td>38.99</td><td>152.77</td><td>  0.700</td><td>25.87</td><td>45.20</td><td>45.91</td><td>228.08</td><td> 2.36</td><td> 1.94</td><td>  0.712</td><td>  0.980</td><td>  0.981</td></tr>
<tr><td align="left">023_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.44</td><td>   8.34</td><td>1</td><td>299</td><td>0</td><td>12.70</td><td>38.97</td><td>153.01</td><td>  0.709</td><td>25.88</td><td>45.20</td><td>45.84</td><td>228.45</td><td> 2.35</td><td> 1.99</td><td>  0.748</td><td>  0.982</td><td>  0.983</td></tr>
<tr><td align="left">023_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.15</td><td>   1.72</td><td>1</td><td>299</td><td>0</td><td>24.81</td><td>39.52</td><td>149.31</td><td>  0.703</td><td>26.01</td><td>45.62</td><td>46.92</td><td>223.04</td><td> 2.17</td><td> 1.55</td><td>  0.671</td><td>  0.977</td><td>  0.980</td></tr>
<tr><td align="left">023_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  21.59</td><td>  17.25</td><td>1</td><td>299</td><td>0</td><td> 9.83</td><td>38.98</td><td>153.02</td><td>  0.702</td><td>25.89</td><td>45.06</td><td>45.99</td><td>228.44</td><td> 2.43</td><td> 1.90</td><td>  0.805</td><td>  0.986</td><td>  0.987</td></tr>
<tr><td align="left">023_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.15</td><td>   2.52</td><td>1</td><td>299</td><td>0</td><td>19.75</td><td>39.17</td><td>152.05</td><td>  0.706</td><td>25.90</td><td>45.52</td><td>46.08</td><td>227.11</td><td> 2.17</td><td> 1.88</td><td>  0.679</td><td>  0.978</td><td>  0.979</td></tr>
<tr><td align="left">023_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  74.61</td><td>  59.63</td><td>1</td><td>299</td><td>0</td><td> 7.46</td><td>38.87</td><td>152.90</td><td>  0.706</td><td>25.91</td><td>45.06</td><td>45.65</td><td>228.23</td><td> 2.43</td><td> 2.08</td><td>  0.898</td><td>  0.992</td><td>  0.992</td></tr>
<tr><td align="left">023_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.12</td><td>   9.69</td><td>2</td><td>76</td><td>222</td><td>15.27</td><td>38.56</td><td>152.91</td><td>  0.700</td><td>25.83</td><td>44.58</td><td>45.26</td><td>228.20</td><td> 2.53</td><td> 2.14</td><td>  0.711</td><td>  0.980</td><td>  0.981</td></tr>
<tr><td align="left">023_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  22.79</td><td>  18.22</td><td>2</td><td>76</td><td>222</td><td>12.60</td><td>38.78</td><td>153.00</td><td>  0.709</td><td>25.85</td><td>44.96</td><td>45.53</td><td>228.41</td><td> 2.41</td><td> 2.07</td><td>  0.746</td><td>  0.981</td><td>  0.982</td></tr>
<tr><td align="left">023_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   5.34</td><td>   4.26</td><td>2</td><td>76</td><td>222</td><td>24.57</td><td>39.30</td><td>148.79</td><td>  0.703</td><td>26.01</td><td>45.48</td><td>46.42</td><td>222.26</td><td> 2.10</td><td> 1.64</td><td>  0.671</td><td>  0.978</td><td>  0.980</td></tr>
<tr><td align="left">023_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  48.51</td><td>  38.77</td><td>2</td><td>76</td><td>222</td><td> 9.81</td><td>38.63</td><td>153.44</td><td>  0.702</td><td>25.84</td><td>44.56</td><td>45.50</td><td>229.00</td><td> 2.59</td><td> 2.08</td><td>  0.803</td><td>  0.985</td><td>  0.986</td></tr>
<tr><td align="left">023_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   7.62</td><td>   6.09</td><td>2</td><td>76</td><td>222</td><td>19.58</td><td>38.97</td><td>151.88</td><td>  0.707</td><td>25.88</td><td>45.27</td><td>45.76</td><td>226.84</td><td> 2.23</td><td> 1.93</td><td>  0.678</td><td>  0.978</td><td>  0.979</td></tr>
<tr><td align="left">023_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 188.43</td><td> 150.59</td><td>2</td><td>76</td><td>222</td><td> 7.43</td><td>38.76</td><td>153.12</td><td>  0.706</td><td>25.92</td><td>44.91</td><td>45.45</td><td>228.52</td><td> 2.49</td><td> 2.16</td><td>  0.897</td><td>  0.991</td><td>  0.991</td></tr>
<tr><td align="left">023_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  11.99</td><td>   9.59</td><td>2</td><td>76</td><td>222</td><td>15.26</td><td>38.67</td><td>152.57</td><td>  0.701</td><td>25.85</td><td>44.75</td><td>45.40</td><td>227.71</td><td> 2.47</td><td> 2.09</td><td>  0.713</td><td>  0.980</td><td>  0.980</td></tr>
<tr><td align="left">023_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  24.50</td><td>  19.58</td><td>2</td><td>76</td><td>222</td><td>12.67</td><td>38.79</td><td>153.93</td><td>  0.708</td><td>25.74</td><td>45.01</td><td>45.62</td><td>229.78</td><td> 2.39</td><td> 2.04</td><td>  0.748</td><td>  0.981</td><td>  0.983</td></tr>
<tr><td align="left">023_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   5.28</td><td>   4.22</td><td>2</td><td>76</td><td>222</td><td>24.62</td><td>39.28</td><td>148.80</td><td>  0.703</td><td>26.01</td><td>45.47</td><td>46.36</td><td>222.25</td><td> 2.12</td><td> 1.68</td><td>  0.671</td><td>  0.977</td><td>  0.979</td></tr>
<tr><td align="left">023_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  49.29</td><td>  39.39</td><td>2</td><td>76</td><td>222</td><td> 9.79</td><td>38.78</td><td>153.07</td><td>  0.702</td><td>25.86</td><td>44.78</td><td>45.69</td><td>228.47</td><td> 2.49</td><td> 2.00</td><td>  0.805</td><td>  0.985</td><td>  0.986</td></tr>
<tr><td align="left">023_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.42</td><td>   5.93</td><td>2</td><td>76</td><td>222</td><td>19.50</td><td>38.84</td><td>154.75</td><td>  0.704</td><td>25.66</td><td>45.28</td><td>45.57</td><td>231.06</td><td> 2.24</td><td> 2.02</td><td>  0.678</td><td>  0.978</td><td>  0.979</td></tr>
<tr><td align="left">023_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 149.82</td><td> 119.73</td><td>2</td><td>76</td><td>222</td><td> 7.44</td><td>38.76</td><td>153.01</td><td>  0.706</td><td>25.89</td><td>44.90</td><td>45.49</td><td>228.38</td><td> 2.46</td><td> 2.11</td><td>  0.898</td><td>  0.991</td><td>  0.992</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 024
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/024_480p.png)](https://drive.google.com/drive/folders/1746B8UPJR77UmERnP9as62Z6PhSLq-3M?usp=share_link)\
*__Figure 25__. First Frame of Sequence 024*

Raw Sequence Size: 19.74 GB\
Source: [HERE](https://drive.google.com/drive/folders/1746B8UPJR77UmERnP9as62Z6PhSLq-3M?usp=share_link)

<br>

*__Table 25__. Description of encoded videos using sequence 024 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">024_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   4.62</td><td>   3.69</td><td>1</td><td>299</td><td>0</td><td>95.07</td><td>44.56</td><td> 9.04</td><td>  0.994</td><td>42.44</td><td>44.88</td><td>46.37</td><td>12.64</td><td> 2.14</td><td> 1.53</td><td>  0.972</td><td>  0.970</td><td>  0.978</td></tr>
<tr><td align="left">024_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.22</td><td>   8.17</td><td>1</td><td>299</td><td>0</td><td>94.39</td><td>42.93</td><td> 9.97</td><td>  0.994</td><td>41.20</td><td>43.01</td><td>44.59</td><td>13.57</td><td> 3.28</td><td> 2.29</td><td>  0.960</td><td>  0.954</td><td>  0.967</td></tr>
<tr><td align="left">024_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.33</td><td>   1.86</td><td>1</td><td>299</td><td>0</td><td>95.67</td><td>48.20</td><td> 7.92</td><td>  0.994</td><td>45.15</td><td>49.03</td><td>50.44</td><td>11.51</td><td> 0.87</td><td> 0.63</td><td>  0.988</td><td>  0.989</td><td>  0.992</td></tr>
<tr><td align="left">024_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  21.32</td><td>  17.04</td><td>1</td><td>299</td><td>0</td><td>92.63</td><td>41.01</td><td>11.76</td><td>  0.994</td><td>39.57</td><td>40.88</td><td>42.58</td><td>15.40</td><td> 5.34</td><td> 3.61</td><td>  0.938</td><td>  0.928</td><td>  0.949</td></tr>
<tr><td align="left">024_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   2.99</td><td>   2.39</td><td>1</td><td>299</td><td>0</td><td>95.49</td><td>46.56</td><td> 8.32</td><td>  0.994</td><td>43.93</td><td>47.18</td><td>48.57</td><td>11.92</td><td> 1.29</td><td> 0.94</td><td>  0.983</td><td>  0.983</td><td>  0.987</td></tr>
<tr><td align="left">024_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  88.90</td><td>  71.05</td><td>1</td><td>299</td><td>0</td><td>84.57</td><td>38.55</td><td>16.01</td><td>  0.994</td><td>37.17</td><td>38.30</td><td>40.17</td><td>20.03</td><td> 9.67</td><td> 6.27</td><td>  0.894</td><td>  0.885</td><td>  0.920</td></tr>
<tr><td align="left">024_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.77</td><td>  11.01</td><td>2</td><td>76</td><td>222</td><td>94.59</td><td>43.05</td><td> 9.74</td><td>  0.993</td><td>41.62</td><td>42.96</td><td>44.57</td><td>13.20</td><td> 3.32</td><td> 2.30</td><td>  0.966</td><td>  0.955</td><td>  0.970</td></tr>
<tr><td align="left">024_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  28.19</td><td>  22.53</td><td>2</td><td>76</td><td>222</td><td>93.72</td><td>41.83</td><td>10.74</td><td>  0.994</td><td>40.53</td><td>41.58</td><td>43.38</td><td>14.21</td><td> 4.57</td><td> 3.03</td><td>  0.953</td><td>  0.938</td><td>  0.957</td></tr>
<tr><td align="left">024_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   4.36</td><td>   3.48</td><td>2</td><td>76</td><td>222</td><td>94.96</td><td>46.10</td><td> 8.33</td><td>  0.993</td><td>44.03</td><td>46.54</td><td>47.74</td><td>11.84</td><td> 1.48</td><td> 1.13</td><td>  0.985</td><td>  0.981</td><td>  0.986</td></tr>
<tr><td align="left">024_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  63.10</td><td>  50.43</td><td>2</td><td>76</td><td>222</td><td>91.84</td><td>40.17</td><td>12.67</td><td>  0.993</td><td>39.05</td><td>39.76</td><td>41.69</td><td>16.16</td><td> 6.95</td><td> 4.46</td><td>  0.929</td><td>  0.909</td><td>  0.939</td></tr>
<tr><td align="left">024_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.80</td><td>   7.03</td><td>2</td><td>76</td><td>222</td><td>94.89</td><td>44.70</td><td> 8.87</td><td>  0.993</td><td>42.84</td><td>44.89</td><td>46.37</td><td>12.39</td><td> 2.14</td><td> 1.53</td><td>  0.978</td><td>  0.971</td><td>  0.979</td></tr>
<tr><td align="left">024_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 257.97</td><td> 206.17</td><td>2</td><td>227</td><td>71</td><td>82.64</td><td>38.22</td><td>17.23</td><td>  0.993</td><td>36.76</td><td>38.03</td><td>39.88</td><td>21.46</td><td>10.62</td><td> 6.91</td><td>  0.881</td><td>  0.875</td><td>  0.914</td></tr>
<tr><td align="left">024_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.99</td><td>  10.38</td><td>2</td><td>76</td><td>222</td><td>94.41</td><td>43.40</td><td> 9.61</td><td>  0.993</td><td>41.64</td><td>43.46</td><td>45.12</td><td>13.17</td><td> 2.96</td><td> 2.03</td><td>  0.966</td><td>  0.960</td><td>  0.972</td></tr>
<tr><td align="left">024_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.29</td><td>  21.01</td><td>2</td><td>76</td><td>222</td><td>86.29</td><td>41.74</td><td>11.45</td><td>  0.993</td><td>39.56</td><td>41.93</td><td>43.74</td><td>15.43</td><td> 4.20</td><td> 2.78</td><td>  0.950</td><td>  0.942</td><td>  0.960</td></tr>
<tr><td align="left">024_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   4.67</td><td>   3.73</td><td>2</td><td>76</td><td>222</td><td>94.89</td><td>46.46</td><td> 8.28</td><td>  0.993</td><td>44.03</td><td>47.02</td><td>48.32</td><td>11.84</td><td> 1.33</td><td> 0.99</td><td>  0.985</td><td>  0.983</td><td>  0.988</td></tr>
<tr><td align="left">024_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.19</td><td>  47.30</td><td>2</td><td>76</td><td>222</td><td>91.72</td><td>40.33</td><td>12.55</td><td>  0.993</td><td>39.06</td><td>40.00</td><td>41.92</td><td>16.14</td><td> 6.55</td><td> 4.21</td><td>  0.929</td><td>  0.913</td><td>  0.942</td></tr>
<tr><td align="left">024_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.70</td><td>   6.95</td><td>2</td><td>76</td><td>222</td><td>82.71</td><td>43.63</td><td>11.62</td><td>  0.990</td><td>38.81</td><td>45.28</td><td>46.81</td><td>16.59</td><td> 1.96</td><td> 1.39</td><td>  0.970</td><td>  0.974</td><td>  0.982</td></tr>
<tr><td align="left">024_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 197.39</td><td> 157.75</td><td>2</td><td>76</td><td>222</td><td>83.68</td><td>38.10</td><td>17.05</td><td>  0.993</td><td>36.78</td><td>37.77</td><td>39.76</td><td>21.11</td><td>10.95</td><td> 6.92</td><td>  0.884</td><td>  0.872</td><td>  0.913</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 025
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/025_480p.png)](https://drive.google.com/drive/folders/1PQtP-u0U8sFXp384uS6vTRnnU8lxnf00?usp=share_link)\
*__Figure 26__. First Frame of Sequence 025*

Raw Sequence Size: 24.69 GB\
Source: [HERE](https://drive.google.com/drive/folders/1PQtP-u0U8sFXp384uS6vTRnnU8lxnf00?usp=share_link)

<br>

*__Table 26__. Description of encoded videos using sequence 025 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">025_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   4.97</td><td>   3.97</td><td>1</td><td>299</td><td>0</td><td>77.81</td><td>38.32</td><td>15.39</td><td>  0.974</td><td>35.70</td><td>37.34</td><td>41.91</td><td>18.98</td><td>12.24</td><td> 4.19</td><td>  0.903</td><td>  0.892</td><td>  0.938</td></tr>
<tr><td align="left">025_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.35</td><td>   8.27</td><td>1</td><td>299</td><td>0</td><td>77.06</td><td>37.00</td><td>18.81</td><td>  0.974</td><td>34.85</td><td>36.04</td><td>40.13</td><td>22.54</td><td>16.41</td><td> 6.33</td><td>  0.859</td><td>  0.843</td><td>  0.909</td></tr>
<tr><td align="left">025_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.42</td><td>   1.93</td><td>1</td><td>299</td><td>0</td><td>71.91</td><td>41.06</td><td>11.30</td><td>  0.974</td><td>37.10</td><td>39.78</td><td>46.30</td><td>14.74</td><td> 7.31</td><td> 1.54</td><td>  0.957</td><td>  0.955</td><td>  0.977</td></tr>
<tr><td align="left">025_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  19.47</td><td>  15.56</td><td>1</td><td>299</td><td>0</td><td>72.24</td><td>35.37</td><td>25.61</td><td>  0.973</td><td>33.49</td><td>34.43</td><td>38.20</td><td>30.03</td><td>23.68</td><td> 9.86</td><td>  0.780</td><td>  0.769</td><td>  0.864</td></tr>
<tr><td align="left">025_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.78</td><td>   3.02</td><td>1</td><td>299</td><td>0</td><td>76.40</td><td>39.85</td><td>12.76</td><td>  0.974</td><td>36.53</td><td>38.70</td><td>44.33</td><td>16.26</td><td> 9.11</td><td> 2.41</td><td>  0.939</td><td>  0.934</td><td>  0.965</td></tr>
<tr><td align="left">025_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  71.63</td><td>  57.25</td><td>1</td><td>299</td><td>0</td><td>55.57</td><td>33.23</td><td>40.64</td><td>  0.972</td><td>31.45</td><td>32.30</td><td>35.94</td><td>47.21</td><td>38.40</td><td>16.58</td><td>  0.654</td><td>  0.666</td><td>  0.799</td></tr>
<tr><td align="left">025_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.62</td><td>  10.09</td><td>2</td><td>290</td><td>8</td><td>77.26</td><td>37.90</td><td>15.96</td><td>  0.973</td><td>35.65</td><td>36.64</td><td>41.41</td><td>19.18</td><td>14.35</td><td> 4.71</td><td>  0.901</td><td>  0.867</td><td>  0.933</td></tr>
<tr><td align="left">025_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  25.87</td><td>  20.68</td><td>2</td><td>298</td><td>0</td><td>76.55</td><td>36.69</td><td>19.35</td><td>  0.974</td><td>34.86</td><td>35.42</td><td>39.78</td><td>22.58</td><td>18.94</td><td> 6.85</td><td>  0.859</td><td>  0.815</td><td>  0.902</td></tr>
<tr><td align="left">025_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.54</td><td>   5.23</td><td>2</td><td>148</td><td>150</td><td>71.62</td><td>40.49</td><td>11.60</td><td>  0.973</td><td>37.06</td><td>39.18</td><td>45.24</td><td>14.85</td><td> 8.26</td><td> 1.95</td><td>  0.956</td><td>  0.941</td><td>  0.971</td></tr>
<tr><td align="left">025_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  58.67</td><td>  46.89</td><td>2</td><td>298</td><td>0</td><td>71.83</td><td>35.02</td><td>26.56</td><td>  0.971</td><td>33.48</td><td>33.81</td><td>37.79</td><td>30.29</td><td>27.36</td><td>10.84</td><td>  0.778</td><td>  0.738</td><td>  0.854</td></tr>
<tr><td align="left">025_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.78</td><td>   7.02</td><td>2</td><td>152</td><td>146</td><td>76.00</td><td>39.32</td><td>13.22</td><td>  0.973</td><td>36.47</td><td>38.04</td><td>43.46</td><td>16.47</td><td>10.54</td><td> 2.94</td><td>  0.937</td><td>  0.913</td><td>  0.958</td></tr>
<tr><td align="left">025_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 275.36</td><td> 220.07</td><td>2</td><td>298</td><td>0</td><td>56.30</td><td>32.92</td><td>44.10</td><td>  0.971</td><td>31.28</td><td>32.05</td><td>35.43</td><td>50.76</td><td>42.29</td><td>19.26</td><td>  0.635</td><td>  0.645</td><td>  0.778</td></tr>
<tr><td align="left">025_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.09</td><td>  10.46</td><td>2</td><td>76</td><td>222</td><td>77.36</td><td>37.97</td><td>16.06</td><td>  0.972</td><td>35.58</td><td>36.82</td><td>41.51</td><td>19.48</td><td>13.82</td><td> 4.60</td><td>  0.897</td><td>  0.873</td><td>  0.934</td></tr>
<tr><td align="left">025_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.38</td><td>  21.09</td><td>2</td><td>76</td><td>222</td><td>73.79</td><td>36.72</td><td>19.75</td><td>  0.973</td><td>34.66</td><td>35.63</td><td>39.87</td><td>23.43</td><td>18.09</td><td> 6.72</td><td>  0.850</td><td>  0.824</td><td>  0.904</td></tr>
<tr><td align="left">025_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.70</td><td>   5.36</td><td>2</td><td>76</td><td>222</td><td>71.59</td><td>40.71</td><td>11.52</td><td>  0.973</td><td>37.05</td><td>39.38</td><td>45.70</td><td>14.86</td><td> 7.92</td><td> 1.76</td><td>  0.955</td><td>  0.946</td><td>  0.975</td></tr>
<tr><td align="left">025_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.88</td><td>  47.06</td><td>2</td><td>76</td><td>222</td><td>72.15</td><td>35.10</td><td>27.07</td><td>  0.971</td><td>33.29</td><td>34.03</td><td>37.97</td><td>31.51</td><td>25.99</td><td>10.42</td><td>  0.766</td><td>  0.749</td><td>  0.859</td></tr>
<tr><td align="left">025_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   9.05</td><td>   7.23</td><td>2</td><td>76</td><td>222</td><td>70.73</td><td>39.44</td><td>13.40</td><td>  0.973</td><td>36.31</td><td>38.23</td><td>43.79</td><td>16.89</td><td>10.11</td><td> 2.73</td><td>  0.934</td><td>  0.919</td><td>  0.961</td></tr>
<tr><td align="left">025_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 200.60</td><td> 160.32</td><td>2</td><td>76</td><td>222</td><td>57.31</td><td>32.84</td><td>44.51</td><td>  0.971</td><td>31.09</td><td>31.87</td><td>35.55</td><td>51.56</td><td>42.63</td><td>18.17</td><td>  0.628</td><td>  0.640</td><td>  0.787</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 026
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/026_480p.png)](https://drive.google.com/drive/folders/1acCPiOXh78ZKhw-OoVFBiNjKsDgxJn7t?usp=share_link)\
*__Figure 27__. First Frame of Sequence 026*

Raw Sequence Size: 21.45 GB\
Source: [HERE](https://drive.google.com/drive/folders/1acCPiOXh78ZKhw-OoVFBiNjKsDgxJn7t?usp=share_link)

<br>

*__Table 27__. Description of encoded videos using sequence 026 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">026_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   6.05</td><td>   4.84</td><td>1</td><td>299</td><td>0</td><td>34.07</td><td>30.91</td><td>310.38</td><td>  0.782</td><td>25.08</td><td>32.39</td><td>35.25</td><td>443.56</td><td>56.11</td><td>31.92</td><td>  0.831</td><td>  0.890</td><td>  0.919</td></tr>
<tr><td align="left">026_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  12.37</td><td>   9.89</td><td>1</td><td>299</td><td>0</td><td>35.31</td><td>30.55</td><td>312.48</td><td>  0.774</td><td>24.98</td><td>31.93</td><td>34.73</td><td>445.62</td><td>59.19</td><td>33.41</td><td>  0.836</td><td>  0.864</td><td>  0.905</td></tr>
<tr><td align="left">026_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.64</td><td>   2.11</td><td>1</td><td>299</td><td>0</td><td>32.90</td><td>31.63</td><td>306.99</td><td>  0.773</td><td>25.28</td><td>33.22</td><td>36.37</td><td>440.25</td><td>52.05</td><td>28.86</td><td>  0.787</td><td>  0.909</td><td>  0.920</td></tr>
<tr><td align="left">026_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  25.13</td><td>  20.08</td><td>1</td><td>299</td><td>0</td><td>33.03</td><td>30.04</td><td>315.92</td><td>  0.782</td><td>24.82</td><td>31.27</td><td>34.05</td><td>448.80</td><td>64.48</td><td>35.83</td><td>  0.831</td><td>  0.826</td><td>  0.885</td></tr>
<tr><td align="left">026_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   4.01</td><td>   3.20</td><td>1</td><td>299</td><td>0</td><td>33.55</td><td>31.34</td><td>308.90</td><td>  0.774</td><td>25.18</td><td>32.91</td><td>35.92</td><td>442.84</td><td>52.88</td><td>29.59</td><td>  0.811</td><td>  0.907</td><td>  0.925</td></tr>
<tr><td align="left">026_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td> 104.08</td><td>  83.18</td><td>1</td><td>299</td><td>0</td><td>30.20</td><td>29.24</td><td>324.59</td><td>  0.778</td><td>24.50</td><td>30.20</td><td>33.03</td><td>457.39</td><td>76.63</td><td>41.35</td><td>  0.799</td><td>  0.765</td><td>  0.850</td></tr>
<tr><td align="left">026_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  15.09</td><td>  12.06</td><td>2</td><td>76</td><td>222</td><td>33.96</td><td>30.73</td><td>310.79</td><td>  0.781</td><td>25.06</td><td>32.13</td><td>34.99</td><td>443.77</td><td>57.34</td><td>32.31</td><td>  0.826</td><td>  0.870</td><td>  0.910</td></tr>
<tr><td align="left">026_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  30.23</td><td>  24.16</td><td>2</td><td>76</td><td>222</td><td>35.23</td><td>30.39</td><td>313.33</td><td>  0.774</td><td>24.97</td><td>31.70</td><td>34.52</td><td>446.32</td><td>60.89</td><td>34.00</td><td>  0.830</td><td>  0.843</td><td>  0.895</td></tr>
<tr><td align="left">026_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   7.44</td><td>   5.95</td><td>2</td><td>76</td><td>222</td><td>32.82</td><td>31.46</td><td>307.41</td><td>  0.771</td><td>25.25</td><td>33.03</td><td>36.11</td><td>440.74</td><td>52.43</td><td>29.04</td><td>  0.783</td><td>  0.898</td><td>  0.915</td></tr>
<tr><td align="left">026_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  67.36</td><td>  53.84</td><td>2</td><td>76</td><td>222</td><td>33.06</td><td>29.86</td><td>317.18</td><td>  0.781</td><td>24.80</td><td>30.97</td><td>33.81</td><td>449.63</td><td>67.55</td><td>37.01</td><td>  0.822</td><td>  0.800</td><td>  0.872</td></tr>
<tr><td align="left">026_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   9.91</td><td>   7.92</td><td>2</td><td>76</td><td>222</td><td>33.44</td><td>31.18</td><td>308.87</td><td>  0.773</td><td>25.16</td><td>32.72</td><td>35.67</td><td>442.44</td><td>53.82</td><td>29.99</td><td>  0.807</td><td>  0.893</td><td>  0.918</td></tr>
<tr><td align="left">026_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 291.71</td><td> 233.14</td><td>2</td><td>283</td><td>15</td><td>29.95</td><td>29.30</td><td>326.49</td><td>  0.777</td><td>24.57</td><td>30.29</td><td>33.04</td><td>459.65</td><td>77.89</td><td>42.45</td><td>  0.783</td><td>  0.754</td><td>  0.840</td></tr>
<tr><td align="left">026_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.10</td><td>  10.47</td><td>2</td><td>76</td><td>222</td><td>33.87</td><td>30.76</td><td>311.00</td><td>  0.781</td><td>25.06</td><td>32.17</td><td>35.06</td><td>444.10</td><td>57.35</td><td>32.25</td><td>  0.826</td><td>  0.873</td><td>  0.912</td></tr>
<tr><td align="left">026_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.89</td><td>  21.49</td><td>2</td><td>76</td><td>222</td><td>33.33</td><td>30.41</td><td>313.60</td><td>  0.774</td><td>24.93</td><td>31.74</td><td>34.57</td><td>446.72</td><td>60.81</td><td>33.90</td><td>  0.829</td><td>  0.847</td><td>  0.897</td></tr>
<tr><td align="left">026_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   7.26</td><td>   5.80</td><td>2</td><td>76</td><td>222</td><td>32.79</td><td>31.48</td><td>307.50</td><td>  0.772</td><td>25.25</td><td>33.05</td><td>36.14</td><td>440.84</td><td>52.54</td><td>29.10</td><td>  0.784</td><td>  0.899</td><td>  0.916</td></tr>
<tr><td align="left">026_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  61.27</td><td>  48.97</td><td>2</td><td>76</td><td>222</td><td>33.06</td><td>29.91</td><td>317.52</td><td>  0.781</td><td>24.80</td><td>31.04</td><td>33.88</td><td>450.33</td><td>66.98</td><td>36.80</td><td>  0.822</td><td>  0.805</td><td>  0.875</td></tr>
<tr><td align="left">026_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   9.85</td><td>   7.87</td><td>2</td><td>76</td><td>222</td><td>30.49</td><td>31.16</td><td>309.38</td><td>  0.771</td><td>25.02</td><td>32.74</td><td>35.72</td><td>443.06</td><td>54.04</td><td>30.02</td><td>  0.805</td><td>  0.894</td><td>  0.919</td></tr>
<tr><td align="left">026_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 201.73</td><td> 161.22</td><td>2</td><td>76</td><td>222</td><td>30.82</td><td>29.17</td><td>326.81</td><td>  0.777</td><td>24.47</td><td>30.12</td><td>32.92</td><td>460.10</td><td>78.12</td><td>42.35</td><td>  0.789</td><td>  0.752</td><td>  0.841</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 027
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/027_480p.png)](https://drive.google.com/drive/folders/1F8o_t2UhfEC8UnkEHO017jht2pYhKyjI?usp=share_link)\
*__Figure 28__. First Frame of Sequence 027*

Raw Sequence Size: 19.49 GB\
Source: [HERE](https://drive.google.com/drive/folders/1F8o_t2UhfEC8UnkEHO017jht2pYhKyjI?usp=share_link)

<br>

*__Table 28__. Description of encoded videos using sequence 027 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">027_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   4.97</td><td>   3.97</td><td>1</td><td>299</td><td>0</td><td>86.46</td><td>43.88</td><td> 5.18</td><td>  0.990</td><td>40.33</td><td>43.38</td><td>47.93</td><td> 6.74</td><td> 3.07</td><td> 1.05</td><td>  0.979</td><td>  0.970</td><td>  0.985</td></tr>
<tr><td align="left">027_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.11</td><td>   7.28</td><td>1</td><td>299</td><td>0</td><td>86.03</td><td>42.83</td><td> 5.90</td><td>  0.989</td><td>39.80</td><td>42.21</td><td>46.49</td><td> 7.48</td><td> 3.99</td><td> 1.46</td><td>  0.972</td><td>  0.957</td><td>  0.979</td></tr>
<tr><td align="left">027_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.46</td><td>   1.97</td><td>1</td><td>299</td><td>0</td><td>87.53</td><td>46.14</td><td> 4.01</td><td>  0.989</td><td>41.47</td><td>45.82</td><td>51.12</td><td> 5.43</td><td> 1.85</td><td> 0.51</td><td>  0.987</td><td>  0.985</td><td>  0.993</td></tr>
<tr><td align="left">027_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  20.71</td><td>  16.55</td><td>1</td><td>299</td><td>0</td><td>84.67</td><td>41.47</td><td> 7.26</td><td>  0.990</td><td>38.90</td><td>40.72</td><td>44.78</td><td> 8.95</td><td> 5.59</td><td> 2.17</td><td>  0.955</td><td>  0.937</td><td>  0.969</td></tr>
<tr><td align="left">027_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.39</td><td>   2.71</td><td>1</td><td>299</td><td>0</td><td>87.00</td><td>45.12</td><td> 4.50</td><td>  0.989</td><td>40.95</td><td>44.77</td><td>49.63</td><td> 6.00</td><td> 2.29</td><td> 0.71</td><td>  0.985</td><td>  0.980</td><td>  0.990</td></tr>
<tr><td align="left">027_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  77.19</td><td>  61.69</td><td>1</td><td>299</td><td>0</td><td>78.95</td><td>39.67</td><td>10.10</td><td>  0.989</td><td>37.44</td><td>38.88</td><td>42.68</td><td>12.15</td><td> 8.47</td><td> 3.52</td><td>  0.917</td><td>  0.905</td><td>  0.952</td></tr>
<tr><td align="left">027_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.28</td><td>  10.62</td><td>2</td><td>76</td><td>222</td><td>86.00</td><td>42.80</td><td> 5.71</td><td>  0.989</td><td>39.99</td><td>42.20</td><td>46.22</td><td> 7.18</td><td> 4.00</td><td> 1.56</td><td>  0.976</td><td>  0.958</td><td>  0.980</td></tr>
<tr><td align="left">027_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.86</td><td>  21.47</td><td>2</td><td>76</td><td>222</td><td>85.48</td><td>41.92</td><td> 6.48</td><td>  0.989</td><td>39.49</td><td>41.16</td><td>45.12</td><td> 7.95</td><td> 5.06</td><td> 2.00</td><td>  0.967</td><td>  0.944</td><td>  0.973</td></tr>
<tr><td align="left">027_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   3.65</td><td>   2.92</td><td>2</td><td>76</td><td>222</td><td>86.76</td><td>44.66</td><td> 4.36</td><td>  0.988</td><td>41.14</td><td>44.40</td><td>48.45</td><td> 5.70</td><td> 2.47</td><td> 0.93</td><td>  0.984</td><td>  0.978</td><td>  0.988</td></tr>
<tr><td align="left">027_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  62.50</td><td>  49.95</td><td>2</td><td>76</td><td>222</td><td>84.00</td><td>40.77</td><td> 8.00</td><td>  0.989</td><td>38.55</td><td>39.92</td><td>43.82</td><td> 9.65</td><td> 6.70</td><td> 2.70</td><td>  0.948</td><td>  0.923</td><td>  0.963</td></tr>
<tr><td align="left">027_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.11</td><td>   6.48</td><td>2</td><td>76</td><td>222</td><td>86.44</td><td>43.89</td><td> 4.92</td><td>  0.989</td><td>40.63</td><td>43.43</td><td>47.61</td><td> 6.33</td><td> 3.05</td><td> 1.13</td><td>  0.982</td><td>  0.970</td><td>  0.985</td></tr>
<tr><td align="left">027_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 251.44</td><td> 200.95</td><td>3</td><td>75</td><td>222</td><td>77.55</td><td>39.24</td><td>11.37</td><td>  0.989</td><td>37.00</td><td>38.56</td><td>42.16</td><td>13.70</td><td> 9.38</td><td> 4.05</td><td>  0.901</td><td>  0.895</td><td>  0.945</td></tr>
<tr><td align="left">027_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.83</td><td>  10.25</td><td>2</td><td>76</td><td>222</td><td>85.91</td><td>43.05</td><td> 5.62</td><td>  0.989</td><td>40.02</td><td>42.46</td><td>46.66</td><td> 7.14</td><td> 3.77</td><td> 1.41</td><td>  0.976</td><td>  0.961</td><td>  0.981</td></tr>
<tr><td align="left">027_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  25.92</td><td>  20.72</td><td>2</td><td>76</td><td>222</td><td>77.88</td><td>41.69</td><td> 8.23</td><td>  0.987</td><td>38.05</td><td>41.42</td><td>45.60</td><td>10.70</td><td> 4.76</td><td> 1.79</td><td>  0.956</td><td>  0.948</td><td>  0.975</td></tr>
<tr><td align="left">027_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   4.44</td><td>   3.55</td><td>2</td><td>76</td><td>222</td><td>86.72</td><td>44.80</td><td> 4.34</td><td>  0.988</td><td>41.14</td><td>44.64</td><td>48.63</td><td> 5.70</td><td> 2.35</td><td> 0.89</td><td>  0.984</td><td>  0.980</td><td>  0.989</td></tr>
<tr><td align="left">027_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.94</td><td>  47.10</td><td>2</td><td>76</td><td>222</td><td>83.85</td><td>40.91</td><td> 7.86</td><td>  0.989</td><td>38.61</td><td>40.03</td><td>44.08</td><td> 9.52</td><td> 6.52</td><td> 2.55</td><td>  0.949</td><td>  0.925</td><td>  0.965</td></tr>
<tr><td align="left">027_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.46</td><td>   6.77</td><td>2</td><td>76</td><td>222</td><td>77.34</td><td>43.07</td><td> 8.63</td><td>  0.982</td><td>37.49</td><td>43.66</td><td>48.07</td><td>11.96</td><td> 2.91</td><td> 1.02</td><td>  0.962</td><td>  0.973</td><td>  0.986</td></tr>
<tr><td align="left">027_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 196.91</td><td> 157.37</td><td>2</td><td>76</td><td>222</td><td>77.81</td><td>39.20</td><td>11.00</td><td>  0.989</td><td>37.12</td><td>38.36</td><td>42.13</td><td>13.11</td><td> 9.56</td><td> 3.99</td><td>  0.907</td><td>  0.893</td><td>  0.946</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 028
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/028_480p.png)](https://drive.google.com/drive/folders/1WxHTv7sT_R9Gend0IDZ2DIzQeCHg5WYV?usp=share_link)\
*__Figure 29__. First Frame of Sequence 028*

Raw Sequence Size: 11.88 GB\
Source: [HERE](https://drive.google.com/drive/folders/1WxHTv7sT_R9Gend0IDZ2DIzQeCHg5WYV?usp=share_link)

<br>

*__Table 29__. Description of encoded videos using sequence 028 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">028_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   6.11</td><td>   4.89</td><td>1</td><td>299</td><td>0</td><td> 9.80</td><td>33.48</td><td>905.82</td><td>  0.468</td><td>17.31</td><td>40.46</td><td>42.66</td><td>1355.99</td><td> 6.73</td><td> 4.22</td><td>  0.644</td><td>  0.978</td><td>  0.985</td></tr>
<tr><td align="left">028_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  11.29</td><td>   9.02</td><td>1</td><td>299</td><td>0</td><td>10.81</td><td>33.37</td><td>905.92</td><td>  0.448</td><td>17.33</td><td>40.30</td><td>42.50</td><td>1356.17</td><td> 7.08</td><td> 4.43</td><td>  0.697</td><td>  0.980</td><td>  0.986</td></tr>
<tr><td align="left">028_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.66</td><td>   2.12</td><td>1</td><td>299</td><td>0</td><td> 8.91</td><td>33.73</td><td>899.97</td><td>  0.447</td><td>17.33</td><td>40.59</td><td>43.28</td><td>1347.36</td><td> 6.54</td><td> 3.86</td><td>  0.490</td><td>  0.964</td><td>  0.978</td></tr>
<tr><td align="left">028_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  23.07</td><td>  18.43</td><td>1</td><td>299</td><td>0</td><td>14.08</td><td>33.30</td><td>906.03</td><td>  0.468</td><td>17.33</td><td>40.19</td><td>42.39</td><td>1356.12</td><td> 7.18</td><td> 4.51</td><td>  0.766</td><td>  0.984</td><td>  0.988</td></tr>
<tr><td align="left">028_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   4.04</td><td>   3.23</td><td>1</td><td>299</td><td>0</td><td> 9.11</td><td>33.43</td><td>903.40</td><td>  0.448</td><td>17.32</td><td>40.77</td><td>42.22</td><td>1352.72</td><td> 6.25</td><td> 4.61</td><td>  0.565</td><td>  0.972</td><td>  0.980</td></tr>
<tr><td align="left">028_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  82.87</td><td>  66.23</td><td>1</td><td>299</td><td>0</td><td>25.69</td><td>33.12</td><td>906.42</td><td>  0.458</td><td>17.34</td><td>40.01</td><td>42.01</td><td>1356.54</td><td> 7.47</td><td> 4.91</td><td>  0.858</td><td>  0.989</td><td>  0.990</td></tr>
<tr><td align="left">028_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  15.30</td><td>  12.23</td><td>2</td><td>125</td><td>173</td><td> 9.84</td><td>33.29</td><td>904.39</td><td>  0.468</td><td>17.31</td><td>40.23</td><td>42.34</td><td>1353.72</td><td> 7.00</td><td> 4.45</td><td>  0.642</td><td>  0.978</td><td>  0.984</td></tr>
<tr><td align="left">028_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  30.49</td><td>  24.37</td><td>2</td><td>154</td><td>144</td><td>10.86</td><td>33.27</td><td>906.22</td><td>  0.448</td><td>17.32</td><td>40.23</td><td>42.27</td><td>1356.57</td><td> 7.12</td><td> 4.60</td><td>  0.695</td><td>  0.980</td><td>  0.986</td></tr>
<tr><td align="left">028_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   7.33</td><td>   5.86</td><td>2</td><td>78</td><td>220</td><td> 8.89</td><td>33.54</td><td>900.94</td><td>  0.445</td><td>17.34</td><td>40.50</td><td>42.78</td><td>1348.72</td><td> 6.59</td><td> 4.14</td><td>  0.487</td><td>  0.963</td><td>  0.977</td></tr>
<tr><td align="left">028_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  67.70</td><td>  54.10</td><td>2</td><td>203</td><td>95</td><td>14.16</td><td>33.23</td><td>905.76</td><td>  0.468</td><td>17.33</td><td>40.11</td><td>42.24</td><td>1355.65</td><td> 7.32</td><td> 4.68</td><td>  0.764</td><td>  0.984</td><td>  0.987</td></tr>
<tr><td align="left">028_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   9.94</td><td>   7.94</td><td>2</td><td>91</td><td>207</td><td> 9.12</td><td>33.36</td><td>902.43</td><td>  0.447</td><td>17.32</td><td>40.58</td><td>42.17</td><td>1351.21</td><td> 6.48</td><td> 4.62</td><td>  0.563</td><td>  0.972</td><td>  0.980</td></tr>
<tr><td align="left">028_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 222.02</td><td> 177.44</td><td>11</td><td>207</td><td>82</td><td>25.88</td><td>33.12</td><td>907.15</td><td>  0.457</td><td>17.41</td><td>40.00</td><td>41.94</td><td>1357.56</td><td> 7.61</td><td> 5.07</td><td>  0.854</td><td>  0.987</td><td>  0.988</td></tr>
<tr><td align="left">028_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.41</td><td>  10.72</td><td>2</td><td>76</td><td>222</td><td> 9.78</td><td>33.34</td><td>904.94</td><td>  0.468</td><td>17.32</td><td>40.26</td><td>42.43</td><td>1354.58</td><td> 6.96</td><td> 4.37</td><td>  0.643</td><td>  0.977</td><td>  0.984</td></tr>
<tr><td align="left">028_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.81</td><td>  21.43</td><td>2</td><td>76</td><td>222</td><td>10.85</td><td>33.29</td><td>906.82</td><td>  0.448</td><td>17.30</td><td>40.22</td><td>42.35</td><td>1357.32</td><td> 7.12</td><td> 4.53</td><td>  0.696</td><td>  0.980</td><td>  0.986</td></tr>
<tr><td align="left">028_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   7.18</td><td>   5.74</td><td>2</td><td>76</td><td>222</td><td> 8.88</td><td>33.51</td><td>901.17</td><td>  0.446</td><td>17.35</td><td>40.46</td><td>42.71</td><td>1349.03</td><td> 6.66</td><td> 4.21</td><td>  0.488</td><td>  0.963</td><td>  0.977</td></tr>
<tr><td align="left">028_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  60.26</td><td>  48.16</td><td>2</td><td>76</td><td>222</td><td>14.12</td><td>33.24</td><td>906.08</td><td>  0.468</td><td>17.34</td><td>40.12</td><td>42.27</td><td>1356.13</td><td> 7.31</td><td> 4.64</td><td>  0.765</td><td>  0.983</td><td>  0.987</td></tr>
<tr><td align="left">028_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>  10.10</td><td>   8.08</td><td>2</td><td>76</td><td>222</td><td> 9.04</td><td>33.31</td><td>903.72</td><td>  0.447</td><td>17.26</td><td>40.55</td><td>42.12</td><td>1352.77</td><td> 6.56</td><td> 4.68</td><td>  0.564</td><td>  0.970</td><td>  0.980</td></tr>
<tr><td align="left">028_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 200.76</td><td> 160.44</td><td>2</td><td>76</td><td>222</td><td>25.90</td><td>33.09</td><td>906.88</td><td>  0.457</td><td>17.34</td><td>39.98</td><td>41.94</td><td>1357.19</td><td> 7.53</td><td> 4.99</td><td>  0.857</td><td>  0.988</td><td>  0.989</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 029
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/029_480p.png)](https://drive.google.com/drive/folders/1Gmb-2hwoxd2TGwEaF1ePp4Ftrt0obBBe?usp=share_link)\
*__Figure 30__. First Frame of Sequence 029*

Raw Sequence Size: 14.94 GB\
Source: [HERE](https://drive.google.com/drive/folders/1Gmb-2hwoxd2TGwEaF1ePp4Ftrt0obBBe?usp=share_link)

<br>

*__Table 30__. Description of encoded videos using sequence 029 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">029_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.02</td><td>   4.01</td><td>1</td><td>299</td><td>0</td><td>75.42</td><td>39.61</td><td>58.13</td><td>  0.968</td><td>35.63</td><td>41.09</td><td>42.11</td><td>79.82</td><td>15.76</td><td>13.76</td><td>  0.976</td><td>  0.981</td><td>  0.985</td></tr>
<tr><td align="left">029_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.01</td><td>   7.20</td><td>1</td><td>299</td><td>0</td><td>75.59</td><td>39.25</td><td>58.55</td><td>  0.966</td><td>35.46</td><td>40.49</td><td>41.79</td><td>80.32</td><td>16.25</td><td>13.78</td><td>  0.977</td><td>  0.978</td><td>  0.986</td></tr>
<tr><td align="left">029_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.32</td><td>   1.85</td><td>1</td><td>299</td><td>0</td><td>74.54</td><td>40.42</td><td>58.16</td><td>  0.965</td><td>36.17</td><td>42.21</td><td>42.89</td><td>80.04</td><td>15.72</td><td>13.11</td><td>  0.967</td><td>  0.978</td><td>  0.980</td></tr>
<tr><td align="left">029_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  19.87</td><td>  15.88</td><td>1</td><td>299</td><td>0</td><td>75.50</td><td>38.77</td><td>58.78</td><td>  0.968</td><td>35.23</td><td>39.69</td><td>41.38</td><td>80.49</td><td>16.82</td><td>13.93</td><td>  0.979</td><td>  0.974</td><td>  0.986</td></tr>
<tr><td align="left">029_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.66</td><td>   2.93</td><td>1</td><td>299</td><td>0</td><td>75.14</td><td>40.05</td><td>58.05</td><td>  0.966</td><td>35.91</td><td>41.65</td><td>42.59</td><td>79.82</td><td>15.90</td><td>13.23</td><td>  0.972</td><td>  0.981</td><td>  0.983</td></tr>
<tr><td align="left">029_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  80.17</td><td>  64.07</td><td>1</td><td>299</td><td>0</td><td>74.65</td><td>38.06</td><td>59.25</td><td>  0.967</td><td>34.86</td><td>38.61</td><td>40.72</td><td>80.85</td><td>17.84</td><td>14.25</td><td>  0.979</td><td>  0.963</td><td>  0.984</td></tr>
<tr><td align="left">029_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  10.76</td><td>   8.60</td><td>2</td><td>76</td><td>222</td><td>75.18</td><td>38.99</td><td>58.51</td><td>  0.967</td><td>35.33</td><td>40.37</td><td>41.27</td><td>80.23</td><td>16.12</td><td>14.03</td><td>  0.974</td><td>  0.976</td><td>  0.983</td></tr>
<tr><td align="left">029_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  22.44</td><td>  17.93</td><td>2</td><td>76</td><td>222</td><td>75.31</td><td>38.70</td><td>58.68</td><td>  0.966</td><td>35.27</td><td>39.72</td><td>41.10</td><td>80.38</td><td>16.63</td><td>13.94</td><td>  0.976</td><td>  0.973</td><td>  0.983</td></tr>
<tr><td align="left">029_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   2.40</td><td>   1.92</td><td>2</td><td>76</td><td>222</td><td>73.65</td><td>39.53</td><td>58.20</td><td>  0.964</td><td>35.64</td><td>41.22</td><td>41.73</td><td>79.95</td><td>15.90</td><td>13.47</td><td>  0.964</td><td>  0.975</td><td>  0.978</td></tr>
<tr><td align="left">029_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  53.54</td><td>  42.79</td><td>2</td><td>76</td><td>222</td><td>75.25</td><td>38.32</td><td>59.05</td><td>  0.968</td><td>35.04</td><td>39.14</td><td>40.79</td><td>80.70</td><td>17.27</td><td>14.23</td><td>  0.977</td><td>  0.967</td><td>  0.983</td></tr>
<tr><td align="left">029_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   5.41</td><td>   4.32</td><td>2</td><td>76</td><td>222</td><td>74.64</td><td>39.12</td><td>58.38</td><td>  0.965</td><td>35.49</td><td>40.46</td><td>41.39</td><td>80.12</td><td>16.24</td><td>13.59</td><td>  0.970</td><td>  0.977</td><td>  0.981</td></tr>
<tr><td align="left">029_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 227.75</td><td> 182.02</td><td>3</td><td>192</td><td>105</td><td>74.24</td><td>37.91</td><td>59.53</td><td>  0.967</td><td>34.68</td><td>38.47</td><td>40.57</td><td>81.16</td><td>18.18</td><td>14.35</td><td>  0.976</td><td>  0.959</td><td>  0.983</td></tr>
<tr><td align="left">029_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.33</td><td>   9.86</td><td>2</td><td>76</td><td>222</td><td>75.03</td><td>39.16</td><td>58.44</td><td>  0.967</td><td>35.39</td><td>40.57</td><td>41.52</td><td>80.17</td><td>16.04</td><td>13.93</td><td>  0.974</td><td>  0.978</td><td>  0.984</td></tr>
<tr><td align="left">029_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  25.87</td><td>  20.67</td><td>2</td><td>76</td><td>222</td><td>70.72</td><td>38.56</td><td>58.93</td><td>  0.965</td><td>34.62</td><td>39.85</td><td>41.21</td><td>80.79</td><td>16.54</td><td>13.89</td><td>  0.974</td><td>  0.974</td><td>  0.984</td></tr>
<tr><td align="left">029_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   2.10</td><td>   1.68</td><td>2</td><td>76</td><td>222</td><td>73.66</td><td>39.60</td><td>58.13</td><td>  0.964</td><td>35.63</td><td>41.35</td><td>41.83</td><td>79.86</td><td>15.85</td><td>13.45</td><td>  0.965</td><td>  0.976</td><td>  0.978</td></tr>
<tr><td align="left">029_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.51</td><td>  46.76</td><td>2</td><td>76</td><td>222</td><td>75.16</td><td>38.43</td><td>58.99</td><td>  0.968</td><td>35.09</td><td>39.27</td><td>40.95</td><td>80.68</td><td>17.13</td><td>14.13</td><td>  0.978</td><td>  0.969</td><td>  0.984</td></tr>
<tr><td align="left">029_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   4.81</td><td>   3.84</td><td>2</td><td>76</td><td>222</td><td>67.56</td><td>38.73</td><td>59.07</td><td>  0.963</td><td>34.11</td><td>40.56</td><td>41.51</td><td>81.17</td><td>16.20</td><td>13.54</td><td>  0.965</td><td>  0.978</td><td>  0.981</td></tr>
<tr><td align="left">029_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 198.06</td><td> 158.29</td><td>2</td><td>76</td><td>222</td><td>74.38</td><td>37.83</td><td>59.42</td><td>  0.967</td><td>34.73</td><td>38.33</td><td>40.45</td><td>80.99</td><td>18.16</td><td>14.41</td><td>  0.978</td><td>  0.959</td><td>  0.983</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 030
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/030_480p.png)](https://drive.google.com/drive/folders/1lgYq24zbyKTusHddLB9U4HsvvexC7Aht?usp=share_link)\
*__Figure 31__. First Frame of Sequence 030*

Raw Sequence Size: 18.30 GB\
Source: [HERE](https://drive.google.com/drive/folders/1lgYq24zbyKTusHddLB9U4HsvvexC7Aht?usp=share_link)

<br>

*__Table 31__. Description of encoded videos using sequence 030 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">030_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.43</td><td>   4.34</td><td>1</td><td>299</td><td>0</td><td>13.64</td><td>30.78</td><td>304.01</td><td>  0.552</td><td>23.05</td><td>30.82</td><td>38.47</td><td>435.71</td><td>69.81</td><td>11.38</td><td>  0.550</td><td>  0.739</td><td>  0.927</td></tr>
<tr><td align="left">030_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.18</td><td>   8.14</td><td>1</td><td>299</td><td>0</td><td>11.41</td><td>30.45</td><td>306.80</td><td>  0.560</td><td>23.01</td><td>30.53</td><td>37.82</td><td>438.76</td><td>73.04</td><td>12.92</td><td>  0.583</td><td>  0.743</td><td>  0.921</td></tr>
<tr><td align="left">030_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.38</td><td>   1.90</td><td>1</td><td>299</td><td>0</td><td>21.64</td><td>31.76</td><td>285.70</td><td>  0.554</td><td>23.53</td><td>32.04</td><td>39.71</td><td>411.43</td><td>58.80</td><td> 9.63</td><td>  0.513</td><td>  0.754</td><td>  0.938</td></tr>
<tr><td align="left">030_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  20.16</td><td>  16.11</td><td>1</td><td>299</td><td>0</td><td> 8.65</td><td>30.23</td><td>308.38</td><td>  0.554</td><td>22.97</td><td>30.30</td><td>37.42</td><td>440.38</td><td>75.01</td><td>13.70</td><td>  0.642</td><td>  0.761</td><td>  0.918</td></tr>
<tr><td align="left">030_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.59</td><td>   2.87</td><td>1</td><td>299</td><td>0</td><td>17.17</td><td>31.15</td><td>297.74</td><td>  0.557</td><td>23.21</td><td>31.37</td><td>38.88</td><td>427.85</td><td>64.39</td><td>11.03</td><td>  0.519</td><td>  0.742</td><td>  0.931</td></tr>
<tr><td align="left">030_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  83.94</td><td>  67.08</td><td>1</td><td>299</td><td>0</td><td> 5.14</td><td>29.84</td><td>310.00</td><td>  0.558</td><td>22.94</td><td>29.95</td><td>36.64</td><td>441.22</td><td>79.35</td><td>15.79</td><td>  0.750</td><td>  0.798</td><td>  0.914</td></tr>
<tr><td align="left">030_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.41</td><td>  10.72</td><td>2</td><td>76</td><td>222</td><td>13.50</td><td>30.88</td><td>302.97</td><td>  0.553</td><td>23.06</td><td>31.06</td><td>38.52</td><td>435.01</td><td>66.52</td><td>11.22</td><td>  0.549</td><td>  0.750</td><td>  0.932</td></tr>
<tr><td align="left">030_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  27.18</td><td>  21.73</td><td>2</td><td>76</td><td>222</td><td>11.34</td><td>30.49</td><td>306.44</td><td>  0.561</td><td>23.00</td><td>30.60</td><td>37.86</td><td>438.72</td><td>71.27</td><td>12.70</td><td>  0.582</td><td>  0.746</td><td>  0.923</td></tr>
<tr><td align="left">030_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.75</td><td>   5.40</td><td>2</td><td>76</td><td>222</td><td>21.36</td><td>31.89</td><td>283.63</td><td>  0.554</td><td>23.57</td><td>32.29</td><td>39.80</td><td>409.23</td><td>55.57</td><td> 9.31</td><td>  0.514</td><td>  0.765</td><td>  0.942</td></tr>
<tr><td align="left">030_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  63.08</td><td>  50.42</td><td>2</td><td>76</td><td>222</td><td> 8.64</td><td>30.23</td><td>308.85</td><td>  0.554</td><td>22.96</td><td>30.37</td><td>37.36</td><td>441.30</td><td>74.07</td><td>13.81</td><td>  0.640</td><td>  0.760</td><td>  0.917</td></tr>
<tr><td align="left">030_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.85</td><td>   7.07</td><td>2</td><td>76</td><td>222</td><td>16.93</td><td>31.20</td><td>295.99</td><td>  0.558</td><td>23.24</td><td>31.36</td><td>38.99</td><td>425.89</td><td>62.26</td><td>10.48</td><td>  0.520</td><td>  0.747</td><td>  0.936</td></tr>
<tr><td align="left">030_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 225.48</td><td> 180.20</td><td>2</td><td>76</td><td>222</td><td> 5.21</td><td>29.94</td><td>310.95</td><td>  0.558</td><td>23.02</td><td>30.08</td><td>36.71</td><td>442.62</td><td>79.23</td><td>15.96</td><td>  0.745</td><td>  0.796</td><td>  0.912</td></tr>
<tr><td align="left">030_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.89</td><td>  10.30</td><td>2</td><td>76</td><td>222</td><td>13.53</td><td>30.84</td><td>302.76</td><td>  0.553</td><td>23.08</td><td>30.96</td><td>38.48</td><td>434.21</td><td>68.32</td><td>11.37</td><td>  0.550</td><td>  0.743</td><td>  0.929</td></tr>
<tr><td align="left">030_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.09</td><td>  20.85</td><td>2</td><td>76</td><td>222</td><td>10.54</td><td>30.39</td><td>308.82</td><td>  0.554</td><td>22.85</td><td>30.51</td><td>37.81</td><td>441.82</td><td>72.77</td><td>12.86</td><td>  0.577</td><td>  0.741</td><td>  0.921</td></tr>
<tr><td align="left">030_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.45</td><td>   5.16</td><td>2</td><td>76</td><td>222</td><td>21.42</td><td>31.83</td><td>284.28</td><td>  0.554</td><td>23.56</td><td>32.22</td><td>39.73</td><td>409.78</td><td>57.03</td><td> 9.56</td><td>  0.513</td><td>  0.760</td><td>  0.939</td></tr>
<tr><td align="left">030_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.24</td><td>  47.35</td><td>2</td><td>76</td><td>222</td><td> 8.62</td><td>30.19</td><td>308.24</td><td>  0.555</td><td>22.99</td><td>30.31</td><td>37.29</td><td>440.02</td><td>75.34</td><td>14.05</td><td>  0.642</td><td>  0.756</td><td>  0.914</td></tr>
<tr><td align="left">030_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.46</td><td>   6.76</td><td>2</td><td>76</td><td>222</td><td>14.91</td><td>31.01</td><td>302.35</td><td>  0.543</td><td>22.89</td><td>31.23</td><td>38.90</td><td>434.72</td><td>64.43</td><td>10.81</td><td>  0.503</td><td>  0.739</td><td>  0.932</td></tr>
<tr><td align="left">030_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 197.00</td><td> 157.44</td><td>2</td><td>76</td><td>222</td><td> 5.17</td><td>29.80</td><td>310.35</td><td>  0.558</td><td>22.96</td><td>29.93</td><td>36.50</td><td>441.47</td><td>79.93</td><td>16.29</td><td>  0.747</td><td>  0.792</td><td>  0.908</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 031
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/031_480p.png)](https://drive.google.com/drive/folders/1-uBPcBo-lnnBb1uV04P5IywzH6563e7o?usp=share_link)\
*__Figure 32__. First Frame of Sequence 031*

Raw Sequence Size:  6.07 GB\
Source: [HERE](https://drive.google.com/drive/folders/1-uBPcBo-lnnBb1uV04P5IywzH6563e7o?usp=share_link)

<br>

*__Table 32__. Description of encoded videos using sequence 031 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">031_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.07</td><td>   4.05</td><td>1</td><td>299</td><td>0</td><td>52.16</td><td>31.27</td><td>501.89</td><td>  0.765</td><td>22.43</td><td>35.70</td><td>35.67</td><td>737.36</td><td>30.98</td><td>30.94</td><td>  0.864</td><td>  0.978</td><td>  0.980</td></tr>
<tr><td align="left">031_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.29</td><td>   7.42</td><td>1</td><td>299</td><td>0</td><td>54.02</td><td>31.26</td><td>502.01</td><td>  0.751</td><td>22.44</td><td>35.72</td><td>35.62</td><td>737.55</td><td>30.71</td><td>31.47</td><td>  0.888</td><td>  0.983</td><td>  0.984</td></tr>
<tr><td align="left">031_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.24</td><td>   1.79</td><td>1</td><td>299</td><td>0</td><td>46.25</td><td>31.29</td><td>502.36</td><td>  0.750</td><td>22.44</td><td>35.74</td><td>35.70</td><td>737.92</td><td>31.06</td><td>31.42</td><td>  0.781</td><td>  0.957</td><td>  0.961</td></tr>
<tr><td align="left">031_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  18.70</td><td>  14.95</td><td>1</td><td>299</td><td>0</td><td>59.28</td><td>31.35</td><td>501.76</td><td>  0.765</td><td>22.46</td><td>35.84</td><td>35.75</td><td>737.42</td><td>30.18</td><td>30.73</td><td>  0.915</td><td>  0.988</td><td>  0.988</td></tr>
<tr><td align="left">031_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.39</td><td>   2.71</td><td>1</td><td>299</td><td>0</td><td>48.17</td><td>31.33</td><td>502.37</td><td>  0.750</td><td>22.42</td><td>35.87</td><td>35.69</td><td>738.56</td><td>29.70</td><td>30.98</td><td>  0.825</td><td>  0.970</td><td>  0.971</td></tr>
<tr><td align="left">031_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  69.01</td><td>  55.15</td><td>1</td><td>299</td><td>0</td><td>71.18</td><td>31.31</td><td>502.10</td><td>  0.758</td><td>22.47</td><td>35.78</td><td>35.70</td><td>737.69</td><td>30.68</td><td>31.21</td><td>  0.946</td><td>  0.993</td><td>  0.993</td></tr>
<tr><td align="left">031_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.61</td><td>  10.08</td><td>2</td><td>105</td><td>193</td><td>52.02</td><td>31.04</td><td>502.41</td><td>  0.764</td><td>22.36</td><td>35.42</td><td>35.34</td><td>738.07</td><td>30.73</td><td>31.47</td><td>  0.862</td><td>  0.977</td><td>  0.978</td></tr>
<tr><td align="left">031_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  25.12</td><td>  20.07</td><td>2</td><td>119</td><td>179</td><td>53.93</td><td>31.13</td><td>502.22</td><td>  0.750</td><td>22.39</td><td>35.53</td><td>35.47</td><td>737.89</td><td>30.69</td><td>31.41</td><td>  0.886</td><td>  0.982</td><td>  0.983</td></tr>
<tr><td align="left">031_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   5.51</td><td>   4.41</td><td>2</td><td>77</td><td>221</td><td>46.12</td><td>31.08</td><td>502.15</td><td>  0.749</td><td>22.37</td><td>35.46</td><td>35.40</td><td>737.63</td><td>30.95</td><td>31.46</td><td>  0.779</td><td>  0.956</td><td>  0.960</td></tr>
<tr><td align="left">031_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  54.56</td><td>  43.61</td><td>2</td><td>161</td><td>137</td><td>59.29</td><td>31.20</td><td>502.41</td><td>  0.764</td><td>22.41</td><td>35.63</td><td>35.56</td><td>738.25</td><td>30.34</td><td>31.10</td><td>  0.913</td><td>  0.987</td><td>  0.987</td></tr>
<tr><td align="left">031_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.03</td><td>   6.42</td><td>2</td><td>83</td><td>215</td><td>48.06</td><td>31.07</td><td>502.33</td><td>  0.750</td><td>22.37</td><td>35.44</td><td>35.39</td><td>738.34</td><td>30.23</td><td>31.11</td><td>  0.823</td><td>  0.969</td><td>  0.970</td></tr>
<tr><td align="left">031_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 182.66</td><td> 145.99</td><td>2</td><td>176</td><td>122</td><td>71.13</td><td>31.28</td><td>502.32</td><td>  0.758</td><td>22.47</td><td>35.72</td><td>35.64</td><td>737.98</td><td>30.75</td><td>31.28</td><td>  0.945</td><td>  0.992</td><td>  0.992</td></tr>
<tr><td align="left">031_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.67</td><td>  10.12</td><td>2</td><td>76</td><td>222</td><td>51.96</td><td>31.08</td><td>502.31</td><td>  0.765</td><td>22.38</td><td>35.47</td><td>35.39</td><td>737.92</td><td>30.76</td><td>31.42</td><td>  0.862</td><td>  0.977</td><td>  0.978</td></tr>
<tr><td align="left">031_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  25.52</td><td>  20.40</td><td>2</td><td>76</td><td>222</td><td>52.06</td><td>31.04</td><td>502.62</td><td>  0.750</td><td>22.08</td><td>35.55</td><td>35.50</td><td>738.39</td><td>30.76</td><td>31.42</td><td>  0.885</td><td>  0.982</td><td>  0.983</td></tr>
<tr><td align="left">031_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   5.09</td><td>   4.07</td><td>2</td><td>76</td><td>222</td><td>46.12</td><td>31.09</td><td>501.95</td><td>  0.749</td><td>22.39</td><td>35.47</td><td>35.41</td><td>737.32</td><td>31.01</td><td>31.44</td><td>  0.780</td><td>  0.956</td><td>  0.960</td></tr>
<tr><td align="left">031_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  56.69</td><td>  45.31</td><td>2</td><td>76</td><td>222</td><td>59.21</td><td>31.22</td><td>502.32</td><td>  0.765</td><td>22.42</td><td>35.67</td><td>35.58</td><td>738.11</td><td>30.37</td><td>31.10</td><td>  0.914</td><td>  0.987</td><td>  0.987</td></tr>
<tr><td align="left">031_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.70</td><td>   6.15</td><td>2</td><td>76</td><td>222</td><td>45.67</td><td>30.86</td><td>503.78</td><td>  0.748</td><td>21.75</td><td>35.44</td><td>35.39</td><td>740.32</td><td>30.33</td><td>31.10</td><td>  0.820</td><td>  0.969</td><td>  0.970</td></tr>
<tr><td align="left">031_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 181.93</td><td> 145.40</td><td>2</td><td>76</td><td>222</td><td>71.23</td><td>31.23</td><td>502.33</td><td>  0.758</td><td>22.44</td><td>35.68</td><td>35.56</td><td>737.99</td><td>30.64</td><td>31.38</td><td>  0.945</td><td>  0.992</td><td>  0.992</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 032
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/032_480p.png)](https://drive.google.com/drive/folders/1XNEH14stdG834bGYfk7Y9Cc_oOcUq0_J?usp=share_link)\
*__Figure 33__. First Frame of Sequence 032*

Raw Sequence Size: 22.35 GB\
Source: [HERE](https://drive.google.com/drive/folders/1XNEH14stdG834bGYfk7Y9Cc_oOcUq0_J?usp=share_link)

<br>

*__Table 33__. Description of encoded videos using sequence 032 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">032_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   4.82</td><td>   3.85</td><td>1</td><td>299</td><td>0</td><td>39.75</td><td>30.03</td><td>450.20</td><td>  0.772</td><td>22.12</td><td>35.92</td><td>32.06</td><td>658.95</td><td>18.94</td><td>46.49</td><td>  0.810</td><td>  0.889</td><td>  0.902</td></tr>
<tr><td align="left">032_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.55</td><td>   7.63</td><td>1</td><td>299</td><td>0</td><td>40.08</td><td>29.62</td><td>453.28</td><td>  0.765</td><td>22.07</td><td>35.02</td><td>31.75</td><td>662.08</td><td>22.87</td><td>48.84</td><td>  0.811</td><td>  0.855</td><td>  0.887</td></tr>
<tr><td align="left">032_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.13</td><td>   1.70</td><td>1</td><td>299</td><td>0</td><td>35.54</td><td>30.83</td><td>446.02</td><td>  0.764</td><td>22.24</td><td>37.59</td><td>32.65</td><td>654.90</td><td>13.88</td><td>42.68</td><td>  0.778</td><td>  0.927</td><td>  0.909</td></tr>
<tr><td align="left">032_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  19.82</td><td>  15.84</td><td>1</td><td>299</td><td>0</td><td>38.25</td><td>29.08</td><td>457.94</td><td>  0.772</td><td>21.99</td><td>33.85</td><td>31.40</td><td>666.65</td><td>29.35</td><td>51.69</td><td>  0.798</td><td>  0.807</td><td>  0.864</td></tr>
<tr><td align="left">032_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.19</td><td>   2.55</td><td>1</td><td>299</td><td>0</td><td>37.00</td><td>30.51</td><td>449.05</td><td>  0.764</td><td>22.17</td><td>36.95</td><td>32.40</td><td>658.78</td><td>15.47</td><td>44.33</td><td>  0.797</td><td>  0.916</td><td>  0.910</td></tr>
<tr><td align="left">032_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  80.63</td><td>  64.44</td><td>1</td><td>299</td><td>0</td><td>31.42</td><td>28.21</td><td>469.27</td><td>  0.768</td><td>21.83</td><td>32.03</td><td>30.77</td><td>678.35</td><td>44.08</td><td>58.14</td><td>  0.759</td><td>  0.734</td><td>  0.828</td></tr>
<tr><td align="left">032_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.15</td><td>   9.71</td><td>2</td><td>76</td><td>222</td><td>39.39</td><td>29.80</td><td>451.47</td><td>  0.771</td><td>22.10</td><td>35.36</td><td>31.95</td><td>660.13</td><td>20.97</td><td>47.34</td><td>  0.805</td><td>  0.868</td><td>  0.893</td></tr>
<tr><td align="left">032_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  24.83</td><td>  19.85</td><td>2</td><td>76</td><td>222</td><td>39.67</td><td>29.41</td><td>453.72</td><td>  0.765</td><td>22.07</td><td>34.49</td><td>31.67</td><td>661.95</td><td>25.30</td><td>49.52</td><td>  0.806</td><td>  0.832</td><td>  0.876</td></tr>
<tr><td align="left">032_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.16</td><td>   4.92</td><td>2</td><td>76</td><td>222</td><td>35.43</td><td>30.64</td><td>445.90</td><td>  0.763</td><td>22.25</td><td>37.15</td><td>32.52</td><td>654.28</td><td>14.85</td><td>43.42</td><td>  0.774</td><td>  0.915</td><td>  0.903</td></tr>
<tr><td align="left">032_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  56.17</td><td>  44.89</td><td>2</td><td>78</td><td>220</td><td>37.91</td><td>28.83</td><td>459.65</td><td>  0.771</td><td>21.98</td><td>33.24</td><td>31.26</td><td>667.86</td><td>33.25</td><td>53.21</td><td>  0.791</td><td>  0.778</td><td>  0.851</td></tr>
<tr><td align="left">032_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.02</td><td>   6.41</td><td>2</td><td>76</td><td>222</td><td>36.75</td><td>30.30</td><td>449.37</td><td>  0.763</td><td>22.16</td><td>36.46</td><td>32.28</td><td>658.78</td><td>16.90</td><td>44.79</td><td>  0.793</td><td>  0.900</td><td>  0.903</td></tr>
<tr><td align="left">032_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 266.68</td><td> 213.13</td><td>2</td><td>273</td><td>25</td><td>30.95</td><td>28.26</td><td>469.41</td><td>  0.768</td><td>21.97</td><td>32.00</td><td>30.80</td><td>677.79</td><td>45.68</td><td>59.62</td><td>  0.748</td><td>  0.723</td><td>  0.817</td></tr>
<tr><td align="left">032_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.13</td><td>  10.49</td><td>2</td><td>76</td><td>222</td><td>39.39</td><td>29.83</td><td>451.54</td><td>  0.771</td><td>22.11</td><td>35.40</td><td>31.97</td><td>660.26</td><td>20.87</td><td>47.30</td><td>  0.806</td><td>  0.869</td><td>  0.894</td></tr>
<tr><td align="left">032_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.21</td><td>  20.94</td><td>2</td><td>76</td><td>222</td><td>38.34</td><td>29.42</td><td>454.32</td><td>  0.765</td><td>22.04</td><td>34.53</td><td>31.69</td><td>662.85</td><td>25.09</td><td>49.43</td><td>  0.803</td><td>  0.834</td><td>  0.878</td></tr>
<tr><td align="left">032_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.28</td><td>   5.02</td><td>2</td><td>76</td><td>222</td><td>35.40</td><td>30.66</td><td>445.78</td><td>  0.763</td><td>22.26</td><td>37.19</td><td>32.54</td><td>654.15</td><td>14.77</td><td>43.33</td><td>  0.775</td><td>  0.916</td><td>  0.904</td></tr>
<tr><td align="left">032_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.68</td><td>  46.90</td><td>2</td><td>76</td><td>222</td><td>38.03</td><td>28.86</td><td>459.94</td><td>  0.771</td><td>21.98</td><td>33.30</td><td>31.30</td><td>668.48</td><td>32.70</td><td>53.05</td><td>  0.791</td><td>  0.781</td><td>  0.853</td></tr>
<tr><td align="left">032_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.20</td><td>   6.55</td><td>2</td><td>76</td><td>222</td><td>33.69</td><td>30.27</td><td>452.59</td><td>  0.760</td><td>21.99</td><td>36.52</td><td>32.30</td><td>663.50</td><td>16.80</td><td>44.72</td><td>  0.784</td><td>  0.902</td><td>  0.904</td></tr>
<tr><td align="left">032_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 196.16</td><td> 156.77</td><td>2</td><td>76</td><td>222</td><td>32.12</td><td>28.06</td><td>471.53</td><td>  0.768</td><td>21.82</td><td>31.70</td><td>30.67</td><td>680.56</td><td>47.11</td><td>59.81</td><td>  0.747</td><td>  0.713</td><td>  0.816</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 033
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/033_480p.png)](https://drive.google.com/drive/folders/13Llz-BrpnPvflcVGEhvKYJxsSGt3VxZ-?usp=share_link)\
*__Figure 34__. First Frame of Sequence 033*

Raw Sequence Size: 15.76 GB\
Source: [HERE](https://drive.google.com/drive/folders/13Llz-BrpnPvflcVGEhvKYJxsSGt3VxZ-?usp=share_link)

<br>

*__Table 34__. Description of encoded videos using sequence 033 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">033_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   4.53</td><td>   3.62</td><td>1</td><td>299</td><td>0</td><td> 6.05</td><td>30.28</td><td>723.79</td><td>  0.774</td><td>19.50</td><td>35.45</td><td>35.89</td><td>1074.50</td><td>24.27</td><td>20.44</td><td>  0.857</td><td>  0.962</td><td>  0.966</td></tr>
<tr><td align="left">033_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   8.60</td><td>   6.87</td><td>1</td><td>299</td><td>0</td><td> 8.38</td><td>30.15</td><td>724.71</td><td>  0.760</td><td>19.48</td><td>35.25</td><td>35.72</td><td>1075.66</td><td>25.10</td><td>21.03</td><td>  0.871</td><td>  0.964</td><td>  0.967</td></tr>
<tr><td align="left">033_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.12</td><td>   1.69</td><td>1</td><td>299</td><td>0</td><td> 3.74</td><td>30.50</td><td>723.85</td><td>  0.759</td><td>19.53</td><td>35.69</td><td>36.30</td><td>1075.12</td><td>23.58</td><td>19.02</td><td>  0.795</td><td>  0.944</td><td>  0.950</td></tr>
<tr><td align="left">033_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  22.06</td><td>  17.63</td><td>1</td><td>299</td><td>0</td><td>15.44</td><td>30.12</td><td>724.73</td><td>  0.774</td><td>19.46</td><td>35.17</td><td>35.72</td><td>1075.63</td><td>25.18</td><td>20.68</td><td>  0.884</td><td>  0.963</td><td>  0.965</td></tr>
<tr><td align="left">033_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.45</td><td>   2.76</td><td>1</td><td>299</td><td>0</td><td> 4.14</td><td>30.40</td><td>726.10</td><td>  0.760</td><td>19.50</td><td>35.44</td><td>36.27</td><td>1078.51</td><td>24.68</td><td>18.92</td><td>  0.829</td><td>  0.954</td><td>  0.959</td></tr>
<tr><td align="left">033_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  76.18</td><td>  60.88</td><td>1</td><td>299</td><td>0</td><td>33.98</td><td>29.83</td><td>725.81</td><td>  0.766</td><td>19.42</td><td>34.77</td><td>35.31</td><td>1076.45</td><td>26.81</td><td>22.24</td><td>  0.893</td><td>  0.957</td><td>  0.958</td></tr>
<tr><td align="left">033_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.37</td><td>  10.68</td><td>2</td><td>86</td><td>212</td><td> 6.05</td><td>30.20</td><td>724.30</td><td>  0.774</td><td>19.49</td><td>35.32</td><td>35.81</td><td>1075.11</td><td>24.82</td><td>20.54</td><td>  0.856</td><td>  0.960</td><td>  0.963</td></tr>
<tr><td align="left">033_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.68</td><td>  21.32</td><td>2</td><td>108</td><td>190</td><td> 8.43</td><td>30.10</td><td>724.87</td><td>  0.760</td><td>19.48</td><td>35.17</td><td>35.67</td><td>1075.82</td><td>25.35</td><td>21.08</td><td>  0.869</td><td>  0.960</td><td>  0.962</td></tr>
<tr><td align="left">033_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   4.83</td><td>   3.86</td><td>2</td><td>76</td><td>222</td><td> 3.74</td><td>30.43</td><td>724.14</td><td>  0.758</td><td>19.51</td><td>35.59</td><td>36.18</td><td>1075.40</td><td>23.90</td><td>19.38</td><td>  0.794</td><td>  0.943</td><td>  0.948</td></tr>
<tr><td align="left">033_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  60.47</td><td>  48.33</td><td>2</td><td>164</td><td>134</td><td>15.56</td><td>30.00</td><td>725.09</td><td>  0.774</td><td>19.46</td><td>35.00</td><td>35.54</td><td>1075.84</td><td>25.85</td><td>21.32</td><td>  0.882</td><td>  0.958</td><td>  0.959</td></tr>
<tr><td align="left">033_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.15</td><td>   6.51</td><td>2</td><td>77</td><td>221</td><td> 4.13</td><td>30.34</td><td>725.23</td><td>  0.759</td><td>19.50</td><td>35.40</td><td>36.11</td><td>1077.08</td><td>24.63</td><td>19.44</td><td>  0.828</td><td>  0.952</td><td>  0.957</td></tr>
<tr><td align="left">033_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 221.77</td><td> 177.24</td><td>3</td><td>291</td><td>6</td><td>34.53</td><td>29.89</td><td>726.38</td><td>  0.766</td><td>19.52</td><td>34.82</td><td>35.35</td><td>1077.16</td><td>27.07</td><td>22.55</td><td>  0.888</td><td>  0.953</td><td>  0.955</td></tr>
<tr><td align="left">033_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.05</td><td>  10.43</td><td>2</td><td>76</td><td>222</td><td> 6.04</td><td>30.22</td><td>724.14</td><td>  0.774</td><td>19.49</td><td>35.35</td><td>35.83</td><td>1074.90</td><td>24.71</td><td>20.50</td><td>  0.856</td><td>  0.960</td><td>  0.963</td></tr>
<tr><td align="left">033_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.18</td><td>  20.92</td><td>2</td><td>76</td><td>222</td><td> 8.34</td><td>30.11</td><td>724.72</td><td>  0.760</td><td>19.46</td><td>35.18</td><td>35.70</td><td>1075.51</td><td>25.29</td><td>20.99</td><td>  0.870</td><td>  0.961</td><td>  0.964</td></tr>
<tr><td align="left">033_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   4.19</td><td>   3.35</td><td>2</td><td>76</td><td>222</td><td> 3.75</td><td>30.43</td><td>723.79</td><td>  0.759</td><td>19.51</td><td>35.58</td><td>36.18</td><td>1074.87</td><td>23.92</td><td>19.36</td><td>  0.794</td><td>  0.944</td><td>  0.949</td></tr>
<tr><td align="left">033_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.26</td><td>  47.36</td><td>2</td><td>76</td><td>222</td><td>15.53</td><td>30.03</td><td>725.11</td><td>  0.774</td><td>19.46</td><td>35.04</td><td>35.59</td><td>1075.94</td><td>25.71</td><td>21.16</td><td>  0.882</td><td>  0.959</td><td>  0.961</td></tr>
<tr><td align="left">033_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.56</td><td>   6.04</td><td>2</td><td>76</td><td>222</td><td> 4.04</td><td>30.32</td><td>724.98</td><td>  0.759</td><td>19.45</td><td>35.41</td><td>36.11</td><td>1076.44</td><td>24.62</td><td>19.49</td><td>  0.829</td><td>  0.953</td><td>  0.958</td></tr>
<tr><td align="left">033_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 197.54</td><td> 157.88</td><td>2</td><td>76</td><td>222</td><td>34.52</td><td>29.80</td><td>726.15</td><td>  0.766</td><td>19.43</td><td>34.72</td><td>35.25</td><td>1076.85</td><td>27.04</td><td>22.49</td><td>  0.890</td><td>  0.953</td><td>  0.955</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 034
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/034_480p.png)](https://drive.google.com/drive/folders/1YmHT6kDsSb2a7yEOUgrhXhwvOGzzfcpA?usp=share_link)\
*__Figure 35__. First Frame of Sequence 034*

Raw Sequence Size: 14.67 GB\
Source: [HERE](https://drive.google.com/drive/folders/1YmHT6kDsSb2a7yEOUgrhXhwvOGzzfcpA?usp=share_link)

<br>

*__Table 35__. Description of encoded videos using sequence 034 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">034_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.62</td><td>   4.49</td><td>1</td><td>299</td><td>0</td><td>16.44</td><td>37.60</td><td>100.35</td><td>  0.753</td><td>27.31</td><td>42.11</td><td>43.39</td><td>148.40</td><td> 4.99</td><td> 3.54</td><td>  0.703</td><td>  0.965</td><td>  0.968</td></tr>
<tr><td align="left">034_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.55</td><td>   8.43</td><td>1</td><td>299</td><td>0</td><td>13.79</td><td>37.29</td><td>103.61</td><td>  0.760</td><td>27.13</td><td>41.86</td><td>42.88</td><td>153.17</td><td> 5.14</td><td> 3.93</td><td>  0.712</td><td>  0.966</td><td>  0.967</td></tr>
<tr><td align="left">034_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.29</td><td>   1.83</td><td>1</td><td>299</td><td>0</td><td>28.63</td><td>38.89</td><td>85.89</td><td>  0.756</td><td>28.23</td><td>43.63</td><td>44.80</td><td>127.19</td><td> 3.84</td><td> 2.77</td><td>  0.713</td><td>  0.967</td><td>  0.970</td></tr>
<tr><td align="left">034_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  21.62</td><td>  17.28</td><td>1</td><td>299</td><td>0</td><td>10.67</td><td>36.93</td><td>106.13</td><td>  0.755</td><td>27.01</td><td>41.35</td><td>42.44</td><td>156.74</td><td> 5.63</td><td> 4.22</td><td>  0.735</td><td>  0.965</td><td>  0.968</td></tr>
<tr><td align="left">034_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.68</td><td>   2.94</td><td>1</td><td>299</td><td>0</td><td>21.72</td><td>38.20</td><td>94.31</td><td>  0.758</td><td>27.67</td><td>42.87</td><td>44.05</td><td>139.63</td><td> 4.31</td><td> 3.14</td><td>  0.700</td><td>  0.966</td><td>  0.969</td></tr>
<tr><td align="left">034_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  78.89</td><td>  63.05</td><td>1</td><td>299</td><td>0</td><td> 7.33</td><td>36.50</td><td>107.34</td><td>  0.759</td><td>26.93</td><td>40.79</td><td>41.77</td><td>158.27</td><td> 6.18</td><td> 4.77</td><td>  0.799</td><td>  0.968</td><td>  0.969</td></tr>
<tr><td align="left">034_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.73</td><td>  10.17</td><td>2</td><td>76</td><td>222</td><td>16.22</td><td>37.54</td><td>100.22</td><td>  0.754</td><td>27.29</td><td>42.03</td><td>43.31</td><td>148.23</td><td> 4.90</td><td> 3.51</td><td>  0.703</td><td>  0.966</td><td>  0.969</td></tr>
<tr><td align="left">034_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  25.40</td><td>  20.30</td><td>2</td><td>76</td><td>222</td><td>13.62</td><td>37.21</td><td>103.44</td><td>  0.761</td><td>27.12</td><td>41.71</td><td>42.78</td><td>152.90</td><td> 5.19</td><td> 3.93</td><td>  0.712</td><td>  0.966</td><td>  0.968</td></tr>
<tr><td align="left">034_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   5.17</td><td>   4.13</td><td>2</td><td>76</td><td>222</td><td>28.30</td><td>38.67</td><td>85.60</td><td>  0.756</td><td>28.22</td><td>43.32</td><td>44.47</td><td>126.76</td><td> 3.82</td><td> 2.78</td><td>  0.714</td><td>  0.967</td><td>  0.970</td></tr>
<tr><td align="left">034_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  55.42</td><td>  44.29</td><td>2</td><td>76</td><td>222</td><td>10.54</td><td>36.86</td><td>106.19</td><td>  0.755</td><td>26.98</td><td>41.24</td><td>42.37</td><td>156.80</td><td> 5.66</td><td> 4.25</td><td>  0.734</td><td>  0.966</td><td>  0.967</td></tr>
<tr><td align="left">034_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.03</td><td>   6.42</td><td>2</td><td>76</td><td>222</td><td>21.44</td><td>38.04</td><td>94.01</td><td>  0.758</td><td>27.67</td><td>42.61</td><td>43.84</td><td>139.16</td><td> 4.41</td><td> 3.18</td><td>  0.701</td><td>  0.966</td><td>  0.969</td></tr>
<tr><td align="left">034_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 200.56</td><td> 160.29</td><td>2</td><td>76</td><td>222</td><td> 7.24</td><td>36.51</td><td>107.50</td><td>  0.759</td><td>26.96</td><td>40.83</td><td>41.73</td><td>158.49</td><td> 6.19</td><td> 4.85</td><td>  0.796</td><td>  0.967</td><td>  0.968</td></tr>
<tr><td align="left">034_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.58</td><td>  10.06</td><td>2</td><td>76</td><td>222</td><td>16.28</td><td>37.53</td><td>100.11</td><td>  0.754</td><td>27.29</td><td>42.03</td><td>43.29</td><td>148.05</td><td> 4.92</td><td> 3.54</td><td>  0.704</td><td>  0.965</td><td>  0.968</td></tr>
<tr><td align="left">034_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  25.20</td><td>  20.14</td><td>2</td><td>76</td><td>222</td><td>12.98</td><td>37.12</td><td>104.36</td><td>  0.758</td><td>26.92</td><td>41.69</td><td>42.75</td><td>154.24</td><td> 5.23</td><td> 3.95</td><td>  0.711</td><td>  0.965</td><td>  0.967</td></tr>
<tr><td align="left">034_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   4.95</td><td>   3.96</td><td>2</td><td>76</td><td>222</td><td>28.32</td><td>38.66</td><td>85.56</td><td>  0.757</td><td>28.22</td><td>43.27</td><td>44.50</td><td>126.69</td><td> 3.86</td><td> 2.78</td><td>  0.714</td><td>  0.967</td><td>  0.970</td></tr>
<tr><td align="left">034_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  56.73</td><td>  45.34</td><td>2</td><td>76</td><td>222</td><td>10.56</td><td>36.86</td><td>105.97</td><td>  0.755</td><td>26.98</td><td>41.26</td><td>42.34</td><td>156.47</td><td> 5.65</td><td> 4.27</td><td>  0.736</td><td>  0.965</td><td>  0.967</td></tr>
<tr><td align="left">034_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.72</td><td>   6.17</td><td>2</td><td>76</td><td>222</td><td>19.96</td><td>37.92</td><td>96.25</td><td>  0.751</td><td>27.33</td><td>42.63</td><td>43.79</td><td>142.46</td><td> 4.43</td><td> 3.23</td><td>  0.695</td><td>  0.965</td><td>  0.968</td></tr>
<tr><td align="left">034_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 191.90</td><td> 153.37</td><td>2</td><td>76</td><td>222</td><td> 7.27</td><td>36.42</td><td>107.28</td><td>  0.759</td><td>26.92</td><td>40.71</td><td>41.63</td><td>158.14</td><td> 6.24</td><td> 4.88</td><td>  0.799</td><td>  0.967</td><td>  0.967</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 035
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/035_480p.png)](https://drive.google.com/drive/folders/1tsKQVAPpNB0gWcTf4YqSafH3Zy3EZMLg?usp=share_link)\
*__Figure 36__. First Frame of Sequence 035*

Raw Sequence Size: 16.50 GB\
Source: [HERE](https://drive.google.com/drive/folders/1tsKQVAPpNB0gWcTf4YqSafH3Zy3EZMLg?usp=share_link)

<br>

*__Table 36__. Description of encoded videos using sequence 035 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">035_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.43</td><td>   4.34</td><td>1</td><td>299</td><td>0</td><td>58.49</td><td>35.72</td><td>870.44</td><td>  0.888</td><td>23.08</td><td>40.43</td><td>43.66</td><td>1300.83</td><td>14.52</td><td> 4.81</td><td>  0.915</td><td>  0.987</td><td>  0.985</td></tr>
<tr><td align="left">035_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.55</td><td>   7.63</td><td>1</td><td>299</td><td>0</td><td>61.88</td><td>35.43</td><td>871.77</td><td>  0.881</td><td>23.03</td><td>40.57</td><td>42.70</td><td>1303.10</td><td>13.27</td><td> 5.61</td><td>  0.916</td><td>  0.984</td><td>  0.978</td></tr>
<tr><td align="left">035_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.48</td><td>   1.98</td><td>1</td><td>299</td><td>0</td><td>46.72</td><td>36.27</td><td>874.45</td><td>  0.880</td><td>23.10</td><td>40.76</td><td>44.94</td><td>1306.97</td><td>14.45</td><td> 4.38</td><td>  0.891</td><td>  0.986</td><td>  0.990</td></tr>
<tr><td align="left">035_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  21.87</td><td>  17.48</td><td>1</td><td>299</td><td>0</td><td>65.49</td><td>34.96</td><td>872.32</td><td>  0.888</td><td>22.98</td><td>39.98</td><td>41.93</td><td>1303.43</td><td>14.14</td><td> 6.07</td><td>  0.912</td><td>  0.979</td><td>  0.967</td></tr>
<tr><td align="left">035_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.73</td><td>   2.98</td><td>1</td><td>299</td><td>0</td><td>52.91</td><td>36.09</td><td>873.10</td><td>  0.880</td><td>23.09</td><td>40.84</td><td>44.35</td><td>1305.39</td><td>13.72</td><td> 4.55</td><td>  0.907</td><td>  0.987</td><td>  0.988</td></tr>
<tr><td align="left">035_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  78.64</td><td>  62.85</td><td>1</td><td>299</td><td>0</td><td>67.56</td><td>34.26</td><td>873.37</td><td>  0.884</td><td>22.89</td><td>39.32</td><td>40.57</td><td>1304.50</td><td>14.83</td><td> 7.38</td><td>  0.902</td><td>  0.972</td><td>  0.953</td></tr>
<tr><td align="left">035_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.30</td><td>  10.63</td><td>2</td><td>116</td><td>182</td><td>58.42</td><td>35.55</td><td>870.38</td><td>  0.887</td><td>23.09</td><td>40.53</td><td>43.02</td><td>1300.79</td><td>13.92</td><td> 5.22</td><td>  0.914</td><td>  0.985</td><td>  0.981</td></tr>
<tr><td align="left">035_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.83</td><td>  21.44</td><td>2</td><td>181</td><td>117</td><td>61.78</td><td>35.17</td><td>872.72</td><td>  0.880</td><td>23.00</td><td>40.28</td><td>42.24</td><td>1304.39</td><td>13.59</td><td> 5.78</td><td>  0.915</td><td>  0.982</td><td>  0.974</td></tr>
<tr><td align="left">035_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   4.13</td><td>   3.30</td><td>2</td><td>83</td><td>215</td><td>46.48</td><td>35.94</td><td>873.95</td><td>  0.879</td><td>23.06</td><td>40.41</td><td>44.34</td><td>1306.25</td><td>14.17</td><td> 4.54</td><td>  0.891</td><td>  0.985</td><td>  0.988</td></tr>
<tr><td align="left">035_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  59.71</td><td>  47.72</td><td>2</td><td>186</td><td>112</td><td>65.54</td><td>34.74</td><td>871.75</td><td>  0.888</td><td>23.01</td><td>39.80</td><td>41.42</td><td>1302.44</td><td>14.30</td><td> 6.40</td><td>  0.912</td><td>  0.977</td><td>  0.963</td></tr>
<tr><td align="left">035_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   7.76</td><td>   6.21</td><td>2</td><td>104</td><td>194</td><td>52.85</td><td>35.88</td><td>871.82</td><td>  0.880</td><td>23.10</td><td>40.76</td><td>43.80</td><td>1303.43</td><td>13.64</td><td> 4.80</td><td>  0.906</td><td>  0.985</td><td>  0.985</td></tr>
<tr><td align="left">035_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 218.11</td><td> 174.31</td><td>2</td><td>298</td><td>0</td><td>68.00</td><td>34.19</td><td>874.41</td><td>  0.884</td><td>22.97</td><td>39.14</td><td>40.46</td><td>1305.90</td><td>15.20</td><td> 7.64</td><td>  0.896</td><td>  0.968</td><td>  0.949</td></tr>
<tr><td align="left">035_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.99</td><td>  10.38</td><td>2</td><td>76</td><td>222</td><td>58.54</td><td>35.64</td><td>870.48</td><td>  0.888</td><td>23.08</td><td>40.62</td><td>43.23</td><td>1300.96</td><td>13.96</td><td> 5.10</td><td>  0.914</td><td>  0.986</td><td>  0.982</td></tr>
<tr><td align="left">035_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.35</td><td>  21.06</td><td>2</td><td>76</td><td>222</td><td>62.44</td><td>35.27</td><td>872.81</td><td>  0.881</td><td>22.98</td><td>40.34</td><td>42.49</td><td>1304.40</td><td>13.60</td><td> 5.62</td><td>  0.915</td><td>  0.984</td><td>  0.976</td></tr>
<tr><td align="left">035_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   3.34</td><td>   2.67</td><td>2</td><td>76</td><td>222</td><td>46.72</td><td>36.03</td><td>874.02</td><td>  0.880</td><td>23.06</td><td>40.40</td><td>44.61</td><td>1306.36</td><td>14.30</td><td> 4.42</td><td>  0.891</td><td>  0.986</td><td>  0.989</td></tr>
<tr><td align="left">035_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.61</td><td>  47.64</td><td>2</td><td>76</td><td>222</td><td>65.41</td><td>34.88</td><td>872.03</td><td>  0.888</td><td>23.00</td><td>39.97</td><td>41.69</td><td>1302.98</td><td>14.10</td><td> 6.17</td><td>  0.912</td><td>  0.979</td><td>  0.966</td></tr>
<tr><td align="left">035_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.24</td><td>   5.79</td><td>2</td><td>76</td><td>222</td><td>54.03</td><td>35.99</td><td>872.01</td><td>  0.881</td><td>23.05</td><td>40.84</td><td>44.07</td><td>1303.44</td><td>13.64</td><td> 4.67</td><td>  0.907</td><td>  0.986</td><td>  0.986</td></tr>
<tr><td align="left">035_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 199.49</td><td> 159.43</td><td>2</td><td>76</td><td>222</td><td>68.07</td><td>34.16</td><td>873.98</td><td>  0.884</td><td>22.87</td><td>39.22</td><td>40.38</td><td>1305.31</td><td>14.99</td><td> 7.62</td><td>  0.897</td><td>  0.970</td><td>  0.950</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 036
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/036_480p.png)](https://drive.google.com/drive/folders/1sH0a5J9zXNoVUMxOQmAjE-CbUWHV_Oln?usp=share_link)\
*__Figure 37__. First Frame of Sequence 036*

Raw Sequence Size: 11.11 GB\
Source: [HERE](https://drive.google.com/drive/folders/1sH0a5J9zXNoVUMxOQmAjE-CbUWHV_Oln?usp=share_link)

<br>

*__Table 37__. Description of encoded videos using sequence 036 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">036_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.05</td><td>   4.03</td><td>1</td><td>299</td><td>0</td><td>54.31</td><td>35.11</td><td>304.54</td><td>  0.783</td><td>22.24</td><td>38.25</td><td>44.85</td><td>453.73</td><td>10.15</td><td> 2.18</td><td>  0.848</td><td>  0.949</td><td>  0.983</td></tr>
<tr><td align="left">036_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  10.09</td><td>   8.07</td><td>1</td><td>299</td><td>0</td><td>57.83</td><td>34.87</td><td>305.15</td><td>  0.776</td><td>22.25</td><td>37.93</td><td>44.44</td><td>454.46</td><td>10.91</td><td> 2.39</td><td>  0.867</td><td>  0.949</td><td>  0.983</td></tr>
<tr><td align="left">036_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.35</td><td>   1.88</td><td>1</td><td>299</td><td>0</td><td>42.51</td><td>35.60</td><td>301.20</td><td>  0.775</td><td>22.30</td><td>38.63</td><td>45.86</td><td>449.01</td><td> 9.43</td><td> 1.73</td><td>  0.793</td><td>  0.944</td><td>  0.983</td></tr>
<tr><td align="left">036_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  22.48</td><td>  17.97</td><td>1</td><td>299</td><td>0</td><td>62.12</td><td>34.84</td><td>305.68</td><td>  0.783</td><td>22.25</td><td>37.72</td><td>44.54</td><td>455.08</td><td>11.45</td><td> 2.33</td><td>  0.891</td><td>  0.951</td><td>  0.984</td></tr>
<tr><td align="left">036_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.33</td><td>   2.67</td><td>1</td><td>299</td><td>0</td><td>48.08</td><td>35.30</td><td>304.01</td><td>  0.775</td><td>22.25</td><td>38.27</td><td>45.38</td><td>453.09</td><td>10.17</td><td> 1.93</td><td>  0.820</td><td>  0.946</td><td>  0.983</td></tr>
<tr><td align="left">036_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  95.34</td><td>  76.19</td><td>1</td><td>299</td><td>0</td><td>65.24</td><td>34.55</td><td>306.58</td><td>  0.779</td><td>22.26</td><td>37.48</td><td>43.92</td><td>456.15</td><td>12.16</td><td> 2.70</td><td>  0.924</td><td>  0.963</td><td>  0.987</td></tr>
<tr><td align="left">036_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.49</td><td>  10.78</td><td>2</td><td>76</td><td>222</td><td>54.17</td><td>34.63</td><td>305.20</td><td>  0.783</td><td>22.22</td><td>37.72</td><td>43.96</td><td>454.29</td><td>11.39</td><td> 2.66</td><td>  0.845</td><td>  0.937</td><td>  0.979</td></tr>
<tr><td align="left">036_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  27.25</td><td>  21.77</td><td>2</td><td>76</td><td>222</td><td>57.67</td><td>34.55</td><td>305.89</td><td>  0.776</td><td>22.23</td><td>37.57</td><td>43.86</td><td>455.25</td><td>11.81</td><td> 2.73</td><td>  0.865</td><td>  0.939</td><td>  0.979</td></tr>
<tr><td align="left">036_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   6.22</td><td>   4.97</td><td>2</td><td>76</td><td>222</td><td>42.33</td><td>35.19</td><td>301.92</td><td>  0.774</td><td>22.30</td><td>38.25</td><td>45.01</td><td>449.81</td><td>10.20</td><td> 2.10</td><td>  0.791</td><td>  0.935</td><td>  0.979</td></tr>
<tr><td align="left">036_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  61.51</td><td>  49.16</td><td>2</td><td>76</td><td>222</td><td>61.92</td><td>34.52</td><td>306.39</td><td>  0.783</td><td>22.24</td><td>37.47</td><td>43.86</td><td>455.87</td><td>12.10</td><td> 2.73</td><td>  0.889</td><td>  0.944</td><td>  0.980</td></tr>
<tr><td align="left">036_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   8.84</td><td>   7.06</td><td>2</td><td>76</td><td>222</td><td>47.90</td><td>34.92</td><td>304.20</td><td>  0.775</td><td>22.25</td><td>37.92</td><td>44.60</td><td>453.10</td><td>10.95</td><td> 2.30</td><td>  0.817</td><td>  0.936</td><td>  0.979</td></tr>
<tr><td align="left">036_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 197.86</td><td> 158.13</td><td>2</td><td>76</td><td>222</td><td>64.83</td><td>34.43</td><td>307.21</td><td>  0.779</td><td>22.29</td><td>37.38</td><td>43.60</td><td>456.92</td><td>12.62</td><td> 2.94</td><td>  0.922</td><td>  0.958</td><td>  0.984</td></tr>
<tr><td align="left">036_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.13</td><td>  10.49</td><td>2</td><td>76</td><td>222</td><td>54.10</td><td>34.75</td><td>304.99</td><td>  0.783</td><td>22.24</td><td>37.79</td><td>44.22</td><td>454.06</td><td>11.22</td><td> 2.51</td><td>  0.845</td><td>  0.939</td><td>  0.980</td></tr>
<tr><td align="left">036_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.34</td><td>  21.05</td><td>2</td><td>76</td><td>222</td><td>47.35</td><td>34.52</td><td>317.03</td><td>  0.773</td><td>21.89</td><td>37.61</td><td>44.05</td><td>471.97</td><td>11.71</td><td> 2.61</td><td>  0.853</td><td>  0.940</td><td>  0.980</td></tr>
<tr><td align="left">036_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.31</td><td>   5.04</td><td>2</td><td>76</td><td>222</td><td>42.33</td><td>35.24</td><td>301.68</td><td>  0.774</td><td>22.31</td><td>38.28</td><td>45.13</td><td>449.48</td><td>10.14</td><td> 2.04</td><td>  0.792</td><td>  0.936</td><td>  0.980</td></tr>
<tr><td align="left">036_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.27</td><td>  47.37</td><td>2</td><td>76</td><td>222</td><td>61.77</td><td>34.59</td><td>306.26</td><td>  0.783</td><td>22.26</td><td>37.50</td><td>44.03</td><td>455.72</td><td>12.07</td><td> 2.63</td><td>  0.889</td><td>  0.944</td><td>  0.981</td></tr>
<tr><td align="left">036_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.66</td><td>   6.92</td><td>2</td><td>76</td><td>222</td><td>38.57</td><td>34.79</td><td>325.42</td><td>  0.765</td><td>21.72</td><td>37.97</td><td>44.67</td><td>484.85</td><td>10.84</td><td> 2.26</td><td>  0.790</td><td>  0.938</td><td>  0.980</td></tr>
<tr><td align="left">036_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 198.07</td><td> 158.30</td><td>2</td><td>76</td><td>222</td><td>64.88</td><td>34.44</td><td>307.08</td><td>  0.779</td><td>22.25</td><td>37.36</td><td>43.72</td><td>456.79</td><td>12.49</td><td> 2.83</td><td>  0.923</td><td>  0.959</td><td>  0.985</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 037
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/037_480p.png)](https://drive.google.com/drive/folders/1-uoD5UDSn9YXsUwF0RuAt-W84JLOm4OT?usp=share_link)\
*__Figure 38__. First Frame of Sequence 037*

Raw Sequence Size:  8.13 GB\
Source: [HERE](https://drive.google.com/drive/folders/1-uoD5UDSn9YXsUwF0RuAt-W84JLOm4OT?usp=share_link)

<br>

*__Table 38__. Description of encoded videos using sequence 037 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">037_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   5.53</td><td>   4.42</td><td>1</td><td>299</td><td>0</td><td>87.91</td><td>40.78</td><td>20.73</td><td>  0.988</td><td>37.88</td><td>37.35</td><td>47.12</td><td>24.03</td><td>26.77</td><td> 1.48</td><td>  0.986</td><td>  0.981</td><td>  0.992</td></tr>
<tr><td align="left">037_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   9.90</td><td>   7.91</td><td>1</td><td>299</td><td>0</td><td>87.33</td><td>40.47</td><td>21.08</td><td>  0.988</td><td>37.76</td><td>37.14</td><td>46.51</td><td>24.37</td><td>27.30</td><td> 1.70</td><td>  0.986</td><td>  0.982</td><td>  0.991</td></tr>
<tr><td align="left">037_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.27</td><td>   1.81</td><td>1</td><td>299</td><td>0</td><td>85.99</td><td>41.46</td><td>20.30</td><td>  0.987</td><td>38.13</td><td>37.91</td><td>48.33</td><td>23.78</td><td>25.56</td><td> 1.11</td><td>  0.984</td><td>  0.979</td><td>  0.993</td></tr>
<tr><td align="left">037_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  22.43</td><td>  17.93</td><td>1</td><td>299</td><td>0</td><td>85.39</td><td>40.45</td><td>21.21</td><td>  0.988</td><td>37.36</td><td>37.16</td><td>46.83</td><td>24.87</td><td>26.26</td><td> 1.53</td><td>  0.986</td><td>  0.983</td><td>  0.992</td></tr>
<tr><td align="left">037_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.58</td><td>   2.86</td><td>1</td><td>299</td><td>0</td><td>87.46</td><td>41.14</td><td>20.38</td><td>  0.987</td><td>37.99</td><td>37.68</td><td>47.76</td><td>23.90</td><td>25.40</td><td> 1.29</td><td>  0.985</td><td>  0.981</td><td>  0.993</td></tr>
<tr><td align="left">037_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  95.40</td><td>  76.24</td><td>1</td><td>299</td><td>0</td><td>80.64</td><td>39.89</td><td>21.98</td><td>  0.987</td><td>36.82</td><td>36.84</td><td>46.02</td><td>25.66</td><td>27.41</td><td> 1.82</td><td>  0.984</td><td>  0.986</td><td>  0.992</td></tr>
<tr><td align="left">037_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.22</td><td>  10.56</td><td>2</td><td>76</td><td>222</td><td>87.73</td><td>40.26</td><td>20.92</td><td>  0.987</td><td>37.72</td><td>36.88</td><td>46.17</td><td>24.26</td><td>26.72</td><td> 1.77</td><td>  0.984</td><td>  0.976</td><td>  0.989</td></tr>
<tr><td align="left">037_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.12</td><td>  20.87</td><td>2</td><td>76</td><td>222</td><td>87.10</td><td>40.15</td><td>21.19</td><td>  0.987</td><td>37.64</td><td>36.79</td><td>46.03</td><td>24.52</td><td>27.22</td><td> 1.82</td><td>  0.985</td><td>  0.976</td><td>  0.988</td></tr>
<tr><td align="left">037_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   3.39</td><td>   2.71</td><td>2</td><td>76</td><td>222</td><td>85.91</td><td>40.83</td><td>20.51</td><td>  0.986</td><td>38.00</td><td>37.37</td><td>47.12</td><td>23.84</td><td>26.30</td><td> 1.41</td><td>  0.983</td><td>  0.976</td><td>  0.990</td></tr>
<tr><td align="left">037_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  59.97</td><td>  47.93</td><td>2</td><td>115</td><td>183</td><td>85.17</td><td>40.03</td><td>21.48</td><td>  0.987</td><td>37.24</td><td>36.78</td><td>46.08</td><td>25.08</td><td>26.79</td><td> 1.76</td><td>  0.984</td><td>  0.977</td><td>  0.988</td></tr>
<tr><td align="left">037_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   7.30</td><td>   5.83</td><td>2</td><td>76</td><td>222</td><td>87.08</td><td>40.54</td><td>20.69</td><td>  0.987</td><td>37.81</td><td>37.16</td><td>46.64</td><td>24.09</td><td>26.24</td><td> 1.57</td><td>  0.984</td><td>  0.976</td><td>  0.990</td></tr>
<tr><td align="left">037_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 204.64</td><td> 163.55</td><td>5</td><td>81</td><td>214</td><td>80.39</td><td>39.74</td><td>22.28</td><td>  0.987</td><td>36.76</td><td>36.76</td><td>45.71</td><td>26.03</td><td>27.59</td><td> 1.95</td><td>  0.983</td><td>  0.983</td><td>  0.990</td></tr>
<tr><td align="left">037_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.16</td><td>  10.52</td><td>2</td><td>76</td><td>222</td><td>87.63</td><td>40.41</td><td>20.91</td><td>  0.987</td><td>37.74</td><td>37.02</td><td>46.47</td><td>24.26</td><td>26.74</td><td> 1.68</td><td>  0.984</td><td>  0.979</td><td>  0.991</td></tr>
<tr><td align="left">037_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.07</td><td>  20.84</td><td>2</td><td>76</td><td>222</td><td>84.19</td><td>40.21</td><td>21.40</td><td>  0.987</td><td>37.37</td><td>36.92</td><td>46.33</td><td>24.86</td><td>27.22</td><td> 1.73</td><td>  0.984</td><td>  0.979</td><td>  0.990</td></tr>
<tr><td align="left">037_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   3.28</td><td>   2.62</td><td>2</td><td>76</td><td>222</td><td>85.90</td><td>40.95</td><td>20.51</td><td>  0.986</td><td>37.99</td><td>37.48</td><td>47.37</td><td>23.88</td><td>26.23</td><td> 1.34</td><td>  0.983</td><td>  0.978</td><td>  0.992</td></tr>
<tr><td align="left">037_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.94</td><td>  47.11</td><td>2</td><td>76</td><td>222</td><td>85.08</td><td>40.18</td><td>21.43</td><td>  0.987</td><td>37.26</td><td>36.92</td><td>46.36</td><td>25.06</td><td>26.69</td><td> 1.68</td><td>  0.984</td><td>  0.980</td><td>  0.990</td></tr>
<tr><td align="left">037_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.38</td><td>   5.89</td><td>2</td><td>76</td><td>222</td><td>83.80</td><td>40.42</td><td>21.22</td><td>  0.985</td><td>37.14</td><td>37.28</td><td>46.83</td><td>24.91</td><td>26.18</td><td> 1.53</td><td>  0.982</td><td>  0.979</td><td>  0.991</td></tr>
<tr><td align="left">037_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 194.92</td><td> 155.78</td><td>2</td><td>76</td><td>222</td><td>80.49</td><td>39.77</td><td>22.21</td><td>  0.987</td><td>36.73</td><td>36.74</td><td>45.84</td><td>26.02</td><td>27.31</td><td> 1.87</td><td>  0.984</td><td>  0.984</td><td>  0.991</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 038
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/038_480p.png)](https://drive.google.com/drive/folders/1H7AhvVj59Gv_FjkfNzLOLR3zAKskQj06?usp=share_link)\
*__Figure 39__. First Frame of Sequence 038*

Raw Sequence Size:  7.40 GB\
Source: [HERE](https://drive.google.com/drive/folders/1H7AhvVj59Gv_FjkfNzLOLR3zAKskQj06?usp=share_link)

<br>

*__Table 39__. Description of encoded videos using sequence 038 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">038_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   6.39</td><td>   5.11</td><td>1</td><td>299</td><td>0</td><td> 4.55</td><td>30.97</td><td>141.68</td><td>  0.682</td><td>25.65</td><td>33.45</td><td>33.80</td><td>195.70</td><td>34.17</td><td>33.12</td><td>  0.786</td><td>  0.910</td><td>  0.934</td></tr>
<tr><td align="left">038_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  11.71</td><td>   9.36</td><td>1</td><td>299</td><td>0</td><td> 4.86</td><td>30.90</td><td>142.13</td><td>  0.674</td><td>25.67</td><td>33.34</td><td>33.68</td><td>195.91</td><td>35.12</td><td>34.14</td><td>  0.826</td><td>  0.917</td><td>  0.941</td></tr>
<tr><td align="left">038_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.69</td><td>   2.15</td><td>1</td><td>299</td><td>0</td><td> 4.33</td><td>31.12</td><td>139.54</td><td>  0.676</td><td>25.68</td><td>33.71</td><td>33.97</td><td>193.03</td><td>32.74</td><td>32.40</td><td>  0.688</td><td>  0.890</td><td>  0.909</td></tr>
<tr><td align="left">038_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  24.01</td><td>  19.19</td><td>1</td><td>299</td><td>0</td><td> 6.93</td><td>30.94</td><td>142.08</td><td>  0.681</td><td>25.69</td><td>33.38</td><td>33.75</td><td>195.99</td><td>34.93</td><td>33.60</td><td>  0.879</td><td>  0.935</td><td>  0.954</td></tr>
<tr><td align="left">038_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   4.10</td><td>   3.27</td><td>1</td><td>299</td><td>0</td><td> 4.03</td><td>31.04</td><td>141.17</td><td>  0.675</td><td>25.63</td><td>33.60</td><td>33.89</td><td>195.33</td><td>33.18</td><td>32.68</td><td>  0.732</td><td>  0.899</td><td>  0.922</td></tr>
<tr><td align="left">038_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  88.12</td><td>  70.42</td><td>1</td><td>299</td><td>0</td><td>20.62</td><td>30.92</td><td>142.47</td><td>  0.676</td><td>25.72</td><td>33.34</td><td>33.72</td><td>196.34</td><td>35.46</td><td>34.00</td><td>  0.944</td><td>  0.964</td><td>  0.974</td></tr>
<tr><td align="left">038_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.86</td><td>  11.08</td><td>2</td><td>107</td><td>191</td><td> 4.52</td><td>30.97</td><td>141.68</td><td>  0.682</td><td>25.65</td><td>33.46</td><td>33.81</td><td>195.76</td><td>34.03</td><td>33.01</td><td>  0.784</td><td>  0.910</td><td>  0.934</td></tr>
<tr><td align="left">038_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  27.57</td><td>  22.04</td><td>2</td><td>85</td><td>213</td><td> 4.93</td><td>30.90</td><td>142.36</td><td>  0.673</td><td>25.66</td><td>33.35</td><td>33.68</td><td>196.34</td><td>34.92</td><td>33.95</td><td>  0.823</td><td>  0.917</td><td>  0.940</td></tr>
<tr><td align="left">038_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   7.09</td><td>   5.67</td><td>2</td><td>76</td><td>222</td><td> 4.38</td><td>31.16</td><td>140.51</td><td>  0.671</td><td>25.67</td><td>33.77</td><td>34.03</td><td>194.71</td><td>32.27</td><td>31.93</td><td>  0.679</td><td>  0.889</td><td>  0.910</td></tr>
<tr><td align="left">038_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  61.97</td><td>  49.53</td><td>2</td><td>76</td><td>222</td><td> 7.10</td><td>30.89</td><td>142.81</td><td>  0.680</td><td>25.67</td><td>33.31</td><td>33.68</td><td>196.92</td><td>35.28</td><td>33.93</td><td>  0.876</td><td>  0.932</td><td>  0.952</td></tr>
<tr><td align="left">038_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   9.23</td><td>   7.38</td><td>2</td><td>76</td><td>222</td><td> 4.05</td><td>31.06</td><td>141.31</td><td>  0.673</td><td>25.64</td><td>33.62</td><td>33.93</td><td>195.68</td><td>32.96</td><td>32.36</td><td>  0.728</td><td>  0.900</td><td>  0.922</td></tr>
<tr><td align="left">038_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 199.17</td><td> 159.18</td><td>3</td><td>173</td><td>124</td><td>20.75</td><td>30.96</td><td>142.81</td><td>  0.676</td><td>25.76</td><td>33.37</td><td>33.75</td><td>196.72</td><td>35.70</td><td>34.24</td><td>  0.942</td><td>  0.962</td><td>  0.972</td></tr>
<tr><td align="left">038_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.09</td><td>  10.46</td><td>2</td><td>76</td><td>222</td><td> 4.53</td><td>30.96</td><td>141.72</td><td>  0.681</td><td>25.68</td><td>33.41</td><td>33.78</td><td>195.65</td><td>34.46</td><td>33.23</td><td>  0.783</td><td>  0.907</td><td>  0.932</td></tr>
<tr><td align="left">038_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.35</td><td>  21.06</td><td>2</td><td>76</td><td>222</td><td> 4.78</td><td>30.89</td><td>142.28</td><td>  0.673</td><td>25.65</td><td>33.34</td><td>33.68</td><td>196.14</td><td>35.14</td><td>33.99</td><td>  0.823</td><td>  0.915</td><td>  0.939</td></tr>
<tr><td align="left">038_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   7.19</td><td>   5.74</td><td>2</td><td>76</td><td>222</td><td> 4.39</td><td>31.14</td><td>140.23</td><td>  0.672</td><td>25.70</td><td>33.73</td><td>34.00</td><td>194.14</td><td>32.65</td><td>32.18</td><td>  0.681</td><td>  0.888</td><td>  0.909</td></tr>
<tr><td align="left">038_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.74</td><td>  47.75</td><td>2</td><td>76</td><td>222</td><td> 7.06</td><td>30.91</td><td>142.65</td><td>  0.680</td><td>25.69</td><td>33.33</td><td>33.70</td><td>196.68</td><td>35.31</td><td>33.89</td><td>  0.876</td><td>  0.932</td><td>  0.951</td></tr>
<tr><td align="left">038_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   9.37</td><td>   7.49</td><td>2</td><td>76</td><td>222</td><td> 3.86</td><td>31.03</td><td>141.30</td><td>  0.673</td><td>25.62</td><td>33.57</td><td>33.89</td><td>195.41</td><td>33.50</td><td>32.68</td><td>  0.727</td><td>  0.897</td><td>  0.920</td></tr>
<tr><td align="left">038_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 196.77</td><td> 157.26</td><td>2</td><td>76</td><td>222</td><td>20.76</td><td>30.90</td><td>142.85</td><td>  0.676</td><td>25.71</td><td>33.32</td><td>33.69</td><td>196.82</td><td>35.64</td><td>34.18</td><td>  0.943</td><td>  0.962</td><td>  0.972</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 039
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/039_480p.png)](https://drive.google.com/drive/folders/1jU6AUf1Vf8ge8Jn7OoCJMPazUiVhcM8F?usp=share_link)\
*__Figure 40__. First Frame of Sequence 039*

Raw Sequence Size: 18.38 GB\
Source: [HERE](https://drive.google.com/drive/folders/1jU6AUf1Vf8ge8Jn7OoCJMPazUiVhcM8F?usp=share_link)

<br>

*__Table 40__. Description of encoded videos using sequence 039 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">039_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   4.45</td><td>   3.56</td><td>1</td><td>299</td><td>0</td><td>81.67</td><td>42.00</td><td>17.49</td><td>  0.984</td><td>36.93</td><td>43.75</td><td>45.31</td><td>24.81</td><td> 3.71</td><td> 2.02</td><td>  0.977</td><td>  0.982</td><td>  0.977</td></tr>
<tr><td align="left">039_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>   8.73</td><td>   6.98</td><td>1</td><td>299</td><td>0</td><td>83.41</td><td>41.19</td><td>17.93</td><td>  0.983</td><td>36.66</td><td>42.84</td><td>44.08</td><td>25.18</td><td> 4.23</td><td> 2.62</td><td>  0.973</td><td>  0.975</td><td>  0.967</td></tr>
<tr><td align="left">039_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.16</td><td>   1.72</td><td>1</td><td>299</td><td>0</td><td>76.75</td><td>43.65</td><td>16.86</td><td>  0.982</td><td>37.40</td><td>45.26</td><td>48.29</td><td>24.22</td><td> 3.17</td><td> 1.12</td><td>  0.980</td><td>  0.988</td><td>  0.991</td></tr>
<tr><td align="left">039_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  20.99</td><td>  16.78</td><td>1</td><td>299</td><td>0</td><td>84.62</td><td>40.14</td><td>18.75</td><td>  0.984</td><td>36.22</td><td>41.81</td><td>42.38</td><td>25.92</td><td> 5.00</td><td> 3.83</td><td>  0.963</td><td>  0.964</td><td>  0.950</td></tr>
<tr><td align="left">039_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   3.74</td><td>   2.99</td><td>1</td><td>299</td><td>0</td><td>78.88</td><td>42.90</td><td>17.14</td><td>  0.983</td><td>37.21</td><td>44.41</td><td>47.10</td><td>24.51</td><td> 3.45</td><td> 1.39</td><td>  0.979</td><td>  0.985</td><td>  0.986</td></tr>
<tr><td align="left">039_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  75.20</td><td>  60.10</td><td>1</td><td>299</td><td>0</td><td>81.85</td><td>38.67</td><td>20.66</td><td>  0.983</td><td>35.41</td><td>40.29</td><td>40.30</td><td>27.79</td><td> 6.65</td><td> 6.15</td><td>  0.941</td><td>  0.943</td><td>  0.922</td></tr>
<tr><td align="left">039_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  12.24</td><td>   9.79</td><td>2</td><td>76</td><td>222</td><td>81.41</td><td>41.23</td><td>17.80</td><td>  0.983</td><td>36.82</td><td>42.93</td><td>43.93</td><td>24.99</td><td> 4.13</td><td> 2.72</td><td>  0.975</td><td>  0.976</td><td>  0.968</td></tr>
<tr><td align="left">039_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.02</td><td>  20.79</td><td>2</td><td>76</td><td>222</td><td>83.11</td><td>40.57</td><td>18.18</td><td>  0.983</td><td>36.53</td><td>42.24</td><td>42.95</td><td>25.28</td><td> 4.62</td><td> 3.36</td><td>  0.970</td><td>  0.968</td><td>  0.956</td></tr>
<tr><td align="left">039_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   3.50</td><td>   2.80</td><td>2</td><td>76</td><td>222</td><td>76.51</td><td>42.92</td><td>16.94</td><td>  0.982</td><td>37.27</td><td>44.62</td><td>46.89</td><td>24.21</td><td> 3.37</td><td> 1.46</td><td>  0.979</td><td>  0.985</td><td>  0.986</td></tr>
<tr><td align="left">039_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  60.24</td><td>  48.14</td><td>2</td><td>150</td><td>148</td><td>84.23</td><td>39.58</td><td>19.19</td><td>  0.984</td><td>36.09</td><td>41.19</td><td>41.45</td><td>26.22</td><td> 5.56</td><td> 4.71</td><td>  0.960</td><td>  0.956</td><td>  0.938</td></tr>
<tr><td align="left">039_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   7.65</td><td>   6.11</td><td>2</td><td>76</td><td>222</td><td>78.52</td><td>42.12</td><td>17.40</td><td>  0.983</td><td>37.06</td><td>43.65</td><td>45.64</td><td>24.69</td><td> 3.80</td><td> 1.86</td><td>  0.978</td><td>  0.981</td><td>  0.979</td></tr>
<tr><td align="left">039_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 247.61</td><td> 197.89</td><td>2</td><td>280</td><td>18</td><td>81.18</td><td>38.41</td><td>21.26</td><td>  0.983</td><td>35.18</td><td>40.00</td><td>40.06</td><td>28.44</td><td> 7.16</td><td> 6.66</td><td>  0.932</td><td>  0.937</td><td>  0.916</td></tr>
<tr><td align="left">039_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  12.67</td><td>  10.13</td><td>2</td><td>76</td><td>222</td><td>81.40</td><td>41.47</td><td>17.70</td><td>  0.983</td><td>36.81</td><td>43.24</td><td>44.35</td><td>24.96</td><td> 3.93</td><td> 2.47</td><td>  0.975</td><td>  0.979</td><td>  0.971</td></tr>
<tr><td align="left">039_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  25.80</td><td>  20.62</td><td>2</td><td>76</td><td>222</td><td>76.67</td><td>40.63</td><td>18.43</td><td>  0.983</td><td>36.25</td><td>42.44</td><td>43.20</td><td>25.73</td><td> 4.49</td><td> 3.18</td><td>  0.969</td><td>  0.971</td><td>  0.959</td></tr>
<tr><td align="left">039_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   3.15</td><td>   2.52</td><td>2</td><td>76</td><td>222</td><td>76.52</td><td>43.13</td><td>16.88</td><td>  0.982</td><td>37.28</td><td>44.84</td><td>47.29</td><td>24.17</td><td> 3.29</td><td> 1.34</td><td>  0.979</td><td>  0.987</td><td>  0.988</td></tr>
<tr><td align="left">039_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  58.84</td><td>  47.03</td><td>2</td><td>76</td><td>222</td><td>84.19</td><td>39.71</td><td>19.14</td><td>  0.983</td><td>36.06</td><td>41.39</td><td>41.67</td><td>26.24</td><td> 5.36</td><td> 4.49</td><td>  0.960</td><td>  0.959</td><td>  0.941</td></tr>
<tr><td align="left">039_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   7.76</td><td>   6.20</td><td>2</td><td>76</td><td>222</td><td>69.94</td><td>42.11</td><td>18.17</td><td>  0.981</td><td>36.22</td><td>43.95</td><td>46.15</td><td>25.92</td><td> 3.67</td><td> 1.67</td><td>  0.975</td><td>  0.983</td><td>  0.982</td></tr>
<tr><td align="left">039_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 197.19</td><td> 157.59</td><td>2</td><td>76</td><td>222</td><td>81.59</td><td>38.34</td><td>21.16</td><td>  0.983</td><td>35.25</td><td>39.97</td><td>39.82</td><td>28.27</td><td> 7.06</td><td> 6.85</td><td>  0.934</td><td>  0.938</td><td>  0.913</td></tr>
</tbody></table>

[Back to Top](#idtext)

___



### Sequence 040
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/040_480p.png)](https://drive.google.com/drive/folders/19YXXi2zxCMBf5oJ_vSJPhDa6McoGf0_V?usp=share_link)\
*__Figure 41__. First Frame of Sequence 040*

Raw Sequence Size: 14.21 GB\
Source: [HERE](https://drive.google.com/drive/folders/19YXXi2zxCMBf5oJ_vSJPhDa6McoGf0_V?usp=share_link)

<br>

*__Table 41__. Description of encoded videos using sequence 040 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File (.mp4)</td><td rowspan="2"><b><i>Codec</td><td rowspan="2"><b><i>Resolution</td><td rowspan="2"><b><i>Pixel Format</td><td rowspan="2"><b><i>File Size (MB)</td><td rowspan="2"><b><i>Bitrate (MB)</td><td colspan="3"><b><i># Frame Types</td><td rowspan="2"><b><i>VMAF</td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN></td><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></td><td colspan="3" align="center"><b><i>PSNR</td><td colspan="3" align="center"><b><i>MSE</td><td colspan="3" align="center"><b><i>SSIM</td></tr>
<tr><td><b><i>I</td><td><b><i>P</td><td><b><i>B</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td><td><b><i>y</td><td><b><i>u</td><td><b><i>v</td></tr><tr><td align="left">040_av1_1K</td><td align="center">AV1</td><td align="center">2048x1080</td><td rowspan="18">yuv420p</td><td>   6.15</td><td>   4.91</td><td>1</td><td>299</td><td>0</td><td> 6.76</td><td>37.77</td><td>182.92</td><td>  0.627</td><td>24.39</td><td>43.58</td><td>45.33</td><td>273.13</td><td> 3.02</td><td> 1.98</td><td>  0.655</td><td>  0.974</td><td>  0.979</td></tr>
<tr><td align="left">040_av1_2K</td><td align="center">AV1</td><td align="center">2731x1440</td><td>  11.53</td><td>   9.22</td><td>1</td><td>299</td><td>0</td><td> 5.58</td><td>37.45</td><td>184.69</td><td>  0.630</td><td>24.36</td><td>43.22</td><td>44.78</td><td>275.69</td><td> 3.26</td><td> 2.24</td><td>  0.685</td><td>  0.973</td><td>  0.977</td></tr>
<tr><td align="left">040_av1_480p</td><td align="center">AV1</td><td align="center">910x480</td><td>   2.71</td><td>   2.17</td><td>1</td><td>299</td><td>0</td><td>12.55</td><td>38.59</td><td>173.44</td><td>  0.627</td><td>24.66</td><td>44.48</td><td>46.64</td><td>259.17</td><td> 2.50</td><td> 1.49</td><td>  0.603</td><td>  0.973</td><td>  0.982</td></tr>
<tr><td align="left">040_av1_4K</td><td align="center">AV1</td><td align="center">4096x2160</td><td>  22.98</td><td>  18.36</td><td>1</td><td>299</td><td>0</td><td> 4.71</td><td>37.10</td><td>185.90</td><td>  0.627</td><td>24.35</td><td>42.91</td><td>44.05</td><td>277.32</td><td> 3.48</td><td> 2.64</td><td>  0.739</td><td>  0.975</td><td>  0.975</td></tr>
<tr><td align="left">040_av1_720p</td><td align="center">AV1</td><td align="center">1365x720</td><td>   4.02</td><td>   3.21</td><td>1</td><td>299</td><td>0</td><td> 8.58</td><td>38.18</td><td>179.53</td><td>  0.629</td><td>24.48</td><td>44.31</td><td>45.76</td><td>268.27</td><td> 2.56</td><td> 1.82</td><td>  0.620</td><td>  0.974</td><td>  0.980</td></tr>
<tr><td align="left">040_av1_8K</td><td align="center">AV1</td><td align="center">8192x4320</td><td>  80.12</td><td>  64.03</td><td>1</td><td>299</td><td>0</td><td> 3.82</td><td>36.70</td><td>186.81</td><td>  0.628</td><td>24.35</td><td>42.47</td><td>43.28</td><td>278.47</td><td> 3.83</td><td> 3.14</td><td>  0.836</td><td>  0.979</td><td>  0.975</td></tr>
<tr><td align="left">040_h264_1K</td><td align="center">H264</td><td align="center">2048x1080</td><td>  13.56</td><td>  10.84</td><td>2</td><td>76</td><td>222</td><td> 6.69</td><td>37.78</td><td>182.58</td><td>  0.629</td><td>24.39</td><td>43.68</td><td>45.27</td><td>272.64</td><td> 2.91</td><td> 1.99</td><td>  0.656</td><td>  0.976</td><td>  0.981</td></tr>
<tr><td align="left">040_h264_2K</td><td align="center">H264</td><td align="center">2731x1440</td><td>  26.82</td><td>  21.43</td><td>2</td><td>79</td><td>219</td><td> 5.56</td><td>37.54</td><td>184.69</td><td>  0.630</td><td>24.36</td><td>43.47</td><td>44.79</td><td>275.75</td><td> 3.06</td><td> 2.22</td><td>  0.684</td><td>  0.976</td><td>  0.978</td></tr>
<tr><td align="left">040_h264_480p</td><td align="center">H264</td><td align="center">910x480</td><td>   7.04</td><td>   5.63</td><td>2</td><td>76</td><td>222</td><td>12.47</td><td>38.58</td><td>174.10</td><td>  0.625</td><td>24.68</td><td>44.66</td><td>46.41</td><td>260.17</td><td> 2.36</td><td> 1.55</td><td>  0.598</td><td>  0.975</td><td>  0.983</td></tr>
<tr><td align="left">040_h264_4K</td><td align="center">H264</td><td align="center">4096x2160</td><td>  61.05</td><td>  48.79</td><td>2</td><td>77</td><td>221</td><td> 4.74</td><td>37.08</td><td>186.20</td><td>  0.627</td><td>24.35</td><td>42.89</td><td>44.01</td><td>277.77</td><td> 3.49</td><td> 2.66</td><td>  0.736</td><td>  0.976</td><td>  0.975</td></tr>
<tr><td align="left">040_h264_720p</td><td align="center">H264</td><td align="center">1365x720</td><td>   9.02</td><td>   7.21</td><td>2</td><td>76</td><td>222</td><td> 8.55</td><td>38.24</td><td>179.63</td><td>  0.629</td><td>24.49</td><td>44.51</td><td>45.74</td><td>268.45</td><td> 2.43</td><td> 1.80</td><td>  0.619</td><td>  0.976</td><td>  0.982</td></tr>
<tr><td align="left">040_h264_8K</td><td align="center">H264</td><td align="center">8192x4320</td><td> 195.90</td><td> 156.56</td><td>2</td><td>78</td><td>220</td><td> 3.87</td><td>36.67</td><td>187.01</td><td>  0.628</td><td>24.42</td><td>42.39</td><td>43.20</td><td>278.72</td><td> 3.95</td><td> 3.24</td><td>  0.832</td><td>  0.978</td><td>  0.974</td></tr>
<tr><td align="left">040_hevc_1K</td><td align="center">HEVC</td><td align="center">2048x1080</td><td>  13.19</td><td>  10.54</td><td>2</td><td>76</td><td>222</td><td> 6.76</td><td>37.66</td><td>182.80</td><td>  0.628</td><td>24.42</td><td>43.46</td><td>45.09</td><td>272.91</td><td> 3.08</td><td> 2.09</td><td>  0.654</td><td>  0.974</td><td>  0.979</td></tr>
<tr><td align="left">040_hevc_2K</td><td align="center">HEVC</td><td align="center">2732x1440</td><td>  26.35</td><td>  21.06</td><td>2</td><td>76</td><td>222</td><td> 5.48</td><td>37.36</td><td>184.82</td><td>  0.629</td><td>24.35</td><td>43.22</td><td>44.53</td><td>275.83</td><td> 3.26</td><td> 2.37</td><td>  0.684</td><td>  0.973</td><td>  0.976</td></tr>
<tr><td align="left">040_hevc_480p</td><td align="center">HEVC</td><td align="center">910x480</td><td>   6.94</td><td>   5.54</td><td>2</td><td>76</td><td>222</td><td>12.47</td><td>38.45</td><td>173.84</td><td>  0.626</td><td>24.69</td><td>44.47</td><td>46.20</td><td>259.73</td><td> 2.49</td><td> 1.63</td><td>  0.600</td><td>  0.973</td><td>  0.982</td></tr>
<tr><td align="left">040_hevc_4K</td><td align="center">HEVC</td><td align="center">4096x2160</td><td>  59.25</td><td>  47.36</td><td>2</td><td>76</td><td>222</td><td> 4.74</td><td>36.99</td><td>185.97</td><td>  0.627</td><td>24.38</td><td>42.77</td><td>43.83</td><td>277.36</td><td> 3.59</td><td> 2.78</td><td>  0.737</td><td>  0.974</td><td>  0.973</td></tr>
<tr><td align="left">040_hevc_720p</td><td align="center">HEVC</td><td align="center">1366x720</td><td>   8.99</td><td>   7.18</td><td>2</td><td>76</td><td>222</td><td> 8.39</td><td>38.01</td><td>180.00</td><td>  0.628</td><td>24.44</td><td>44.23</td><td>45.36</td><td>268.85</td><td> 2.61</td><td> 1.97</td><td>  0.618</td><td>  0.974</td><td>  0.980</td></tr>
<tr><td align="left">040_hevc_8K</td><td align="center">HEVC</td><td align="center">8192x4320</td><td> 197.32</td><td> 157.70</td><td>2</td><td>76</td><td>222</td><td> 3.85</td><td>36.58</td><td>186.91</td><td>  0.628</td><td>24.36</td><td>42.34</td><td>43.03</td><td>278.54</td><td> 3.94</td><td> 3.32</td><td>  0.834</td><td>  0.978</td><td>  0.973</td></tr>
</tbody></table>

[Back to Top](#idtext)

___




## FFmpeg Commands

### Video Encoding Commands
**Base video encoding script**
```
ffmpeg -framerate 30000/1001 -pattern_type glob -i "${sequenceID}/*.png" -vf scale=-1:${scale} -b:v ${bitrate}$ -c:v ${encoder} -preset ${preset} "${sequenceID}_${codec}_${resolution}"
```
<br>

*__Table  42__. Variable alternatives used in generating encoded videos*
<table>

  <tr>
    <th>Variable</th>
    <th>Alternative</th>
    <th>Value</th>
  </tr>

  <tr>
    <td><code>${sequenceID}</code></td>
    <td>-</td>
    <td>from 000 to 040</td>
  </tr>
  <tr>
    <td rowspan="6"><code>${scale}</code></td>
    <td>8K</td>
    <td><code>4320</code></td>
  </tr>
  <tr>
    <td>4K</td>
    <td><code>2160</code></td>
  </tr>
  <tr>
    <td>2K</td>
    <td><code>1440</code></td>
  </tr>
  <tr>
    <td>1K</td>
    <td><code>1080</code></td>
  </tr>
  <tr>
    <td>720p</td>
    <td><code>720</code></td>
  </tr>
  <tr>
    <td>480p</td>
    <td><code>480</code></td>
  </tr>
  <tr>
    <td><code>${bitrate}</code></td>
    <td>-</td>
    <td>Depends on the required value. <br>Refer to <a href='#bitrates-used-for-each-video-codec-and-resolution-combination'>Table 1 </a> for the values used.</td>
  </tr>
  <tr>
    <td rowspan="3"><code>${encoder}</code></td>
    <td>HEVC/H265</td>
    <td><code>hevc_nvenc</code></td>
  </tr>
  <tr>
    <td>AVC/H264</td>
    <td><code>h264_nvenc</code></td>
  </tr>
  <tr>
    <td>AV1</td>
    <td><code>libaom-av1</code></td>
  </tr>
  <tr>
    <td rowspan="3"><code>${presets}</code></td>
    <td>HEVC/H265</td>
    <td><code>18</code></td>
  </tr>
  <tr>
    <td>AVC/H264</td>
    <td><code>18</code></td>
  </tr>
  <tr>
    <td>AV1</td>
    <td><code>slow</code></td>
  </tr>
</table>


[Back to Top](#idtext)

___



### Image Transforming Commands
**Base image transforming script**
```
ffmpeg -i "${imageID}/*.tif" -vf scale=-1:${scale} "${imageID}_${codec}_${resolution}.${extention}"
```
<br>

*__Table  43__. Variable alternatives used in generating encoded videos*
<table>

  <tr>
    <th>Variable</th>
    <th>Alternative</th>
    <th>Value</th>
  </tr>

  <tr>
    <td><code>${imageID}</code></td>
    <td>-</td>
    <td>from 000 to 040</td>
  </tr>
  <tr>
    <td rowspan="6"><code>${scale}</code></td>
    <td>8K</td>
    <td><code>4320</code></td>
  </tr>
  <tr>
    <td>4K</td>
    <td><code>2160</code></td>
  </tr>
  <tr>
    <td>2K</td>
    <td><code>1440</code></td>
  </tr>
  <tr>
    <td>1K</td>
    <td><code>1080</code></td>
  </tr>
  <tr>
    <td>720p</td>
    <td><code>720</code></td>
  </tr>
  <tr>
    <td>480p</td>
    <td><code>480</code></td>
  </tr>
  <tr>
    <td rowspan="3"><code>${extention}</code></td>
    <td>PNG</td>
    <td><code>png</code></td>
  </tr>
  <tr>
    <td>JPEG</td>
    <td><code>jpg</code></td>
  </tr>
  <tr>
    <td>WEBP</td>
    <td><code>webp</code></td>
  </tr>
</table>


[Back to Top](#idtext)

___


## Video Sequences Average RBG Histogram over time.
![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/Seq_Hist.png)
*__Figure 42.__ Average RBG Histogram over time for all the sequences in the SEPE dataset*

[Back to Top](#idtext)
___


## Images Histogram over time.
![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/Images_Hist.png)
*__Figure 43.__ RBG Histogram for all images in the SEPE dataset*

[Back to Top](#idtext)

___


