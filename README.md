<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Model based Statistics</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
            background-color: #f9f9f9;
        }
        h1 {
            text-align: center;
        }
        table {
            border-collapse: collapse;
            width: 100%;
            background-color: white;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

<h1>Model based Statistics</h1>

<table>
    <thead>
        <tr>
            <th>Rank</th>
            <th>Model</th>
            <th>LFCC</th>
            <th>MFCC</th>
            <th>GFCC</th>
            <th>Average Accuracy</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>1</td><td>sparktts</td><td>2.4</td><td>17.03</td><td>0.2</td><td>6.54</td></tr>
        <tr><td>2</td><td>fish-speech</td><td>3</td><td>0</td><td>12</td><td>5.00</td></tr>
        <tr><td>3</td><td>nemo tts</td><td>4.4</td><td>17.8</td><td>4.9</td><td>9.03</td></tr>
        <tr><td>4</td><td>viettts</td><td>7.2</td><td>21.7</td><td>100</td><td>42.97</td></tr>
        <tr><td>5</td><td>banglatts</td><td>10</td><td>17</td><td>83.5</td><td>36.83</td></tr>
        <tr><td>6</td><td>openspeech</td><td>14.57</td><td>2</td><td>100</td><td>38.19</td></tr>
        <tr><td>7</td><td>rasatts</td><td>31.5</td><td>9.5</td><td>18.5</td><td>19.83</td></tr>
        <tr><td>8</td><td>parellel_wavegan</td><td>1.59</td><td>4.71</td><td>12.6</td><td>6.30</td></tr>
        <tr><td>9</td><td>overflow</td><td>38.34</td><td>91.99</td><td>5.91</td><td>45.41</td></tr>
        <tr><td>10</td><td>fast_pitch</td><td>35.61</td><td>90.57</td><td>9.43</td><td>45.20</td></tr>
        <tr><td>11</td><td>whisperspeech</td><td>32.94</td><td>25.41</td><td>84.54</td><td>47.63</td></tr>
        <tr><td>12</td><td>xtts</td><td>97.81</td><td>3.54</td><td>9.55</td><td>36.97</td></tr>
        <tr><td>13</td><td>fc_hifi</td><td>81.39</td><td>4.4</td><td>10.36</td><td>32.05</td></tr>
        <tr><td>14</td><td>tortoisetts</td><td>63.67</td><td>11</td><td>14</td><td>29.56</td></tr>
        <tr><td>15</td><td>hifigan</td><td>92.14</td><td>64.58</td><td>13.97</td><td>56.90</td></tr>
        <tr><td>16</td><td>bigvgan</td><td>91.61</td><td>63.22</td><td>14.85</td><td>56.56</td></tr>
        <tr><td>17</td><td>neuralhmm</td><td>23.07</td><td>93.08</td><td>3.51</td><td>39.89</td></tr>
        <tr><td>18</td><td>speedyspeech</td><td>49.54</td><td>99.69</td><td>0</td><td>49.74</td></tr>
        <tr><td>19</td><td>pyttsx3</td><td>42.59</td><td>32.77</td><td>71.84</td><td>49.07</td></tr>
        <tr><td>20</td><td>styletts2</td><td>1.6</td><td>57.8</td><td>100</td><td>53.13</td></tr>
        <tr><td>21</td><td>glowtts</td><td>89.77</td><td>97.89</td><td>3.01</td><td>63.56</td></tr>
        <tr><td>22</td><td>melgan</td><td>89.77</td><td>97.89</td><td>3.01</td><td>63.56</td></tr>
        <tr><td>23</td><td>f5tts</td><td>19.15</td><td>30.9</td><td>100</td><td>50.02</td></tr>
        <tr><td>24</td><td>parlertts</td><td>41.5</td><td>56.86</td><td>82.39</td><td>60.25</td></tr>
        <tr><td>25</td><td>vall-e-x_vc</td><td>22.39</td><td>57.35</td><td>71.28</td><td>50.34</td></tr>
        <tr><td>26</td><td>vall-e-x_tts</td><td>22.39</td><td>57.35</td><td>71.28</td><td>50.34</td></tr>
        <tr><td>27</td><td>bark</td><td>77.1</td><td>70.8</td><td>30.25</td><td>59.38</td></tr>
        <tr><td>28</td><td>kokoro</td><td>10.42</td><td>95.99</td><td>100</td><td>68.80</td></tr>
        <tr><td>29</td><td>diff_hiervc</td><td>98.45</td><td>83.57</td><td>8.77</td><td>63.60</td></tr>
        <tr><td>30</td><td>tracoton2</td><td>100</td><td>58.97</td><td>1.63</td><td>53.53</td></tr>
        <tr><td>31</td><td>openvoicev2</td><td>56.99</td><td>70.85</td><td>99.73</td><td>75.86</td></tr>
        <tr><td>32</td><td>speecht5</td><td>76.91</td><td>80.91</td><td>99.51</td><td>85.78</td></tr>
        <tr><td>33</td><td>mellotts</td><td>76.91</td><td>80.91</td><td>99.51</td><td>85.78</td></tr>
        <tr><td>34</td><td>fastspeech</td><td>73.98</td><td>88.85</td><td>98.76</td><td>87.20</td></tr>
        <tr><td>35</td><td>free_vc</td><td>69.13</td><td>90.75</td><td>36.88</td><td>65.59</td></tr>
        <tr><td>36</td><td>jennytts</td><td>46.04</td><td>99.1</td><td>50.75</td><td>65.30</td></tr>
        <tr><td>37</td><td>germantts</td><td>97.23</td><td>61.62</td><td>50.55</td><td>69.80</td></tr>
        <tr><td>38</td><td>fireredtts</td><td>48.09</td><td>97.49</td><td>98.91</td><td>81.50</td></tr>
        <tr><td>39</td><td>wavegrad</td><td>87.64</td><td>100</td><td>99.8</td><td>95.81</td></tr>
        <tr><td>40</td><td>mms</td><td>99.74</td><td>86.65</td><td>75.38</td><td>87.26</td></tr>
        <tr><td>41</td><td>yourtts</td><td>100</td><td>86.81</td><td>0.06</td><td>62.29</td></tr>
        <tr><td>42</td><td>gtts</td><td>99.17</td><td>95.92</td><td>99.51</td><td>98.20</td></tr>
        <tr><td>43</td><td>vakshya</td><td>98.5</td><td>100</td><td>100</td><td>99.50</td></tr>
        <tr><td>44</td><td>silerotts</td><td>26.2</td><td>40.2</td><td>71.37</td><td>45.92</td></tr>
        <tr><td>45</td><td>nemo tts</td><td>4.4</td><td>17.8</td><td>4.9</td><td>9.03</td></tr>
        <tr><td>46</td><td>kokoro</td><td>10.42</td><td>95.99</td><td>100</td><td>68.80</td></tr>
        <tr><td>47</td><td>speecht5</td><td>76.91</td><td>80.91</td><td>99.51</td><td>85.78</td></tr>
    </tbody>
</table>

</body>
</html>
