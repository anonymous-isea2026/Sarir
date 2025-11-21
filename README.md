# Small Data Generative AI for Culturally Specific Artistic Creation: A Case Study on the Sonic Space of *sarīr*

ISEA 2026 Anonymous Submission

---

## 1. Audio and Spectrogram Samples from the *sarīr* Dataset

<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 1</strong>
    <audio src="resources/audios/r1-1-136.wav" controls></audio>
    <img src="resources/spectrograms/r1-1-136.png" width="300"/>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 2</strong>
    <audio src="resources/audios/r2-1-23.wav" controls></audio>
    <img src="resources/spectrograms/r2-1-23.png" width="300"/>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 3</strong>
    <audio src="resources/audios/r2-1-142.wav" controls></audio>
    <img src="resources/spectrograms/r2-1-142.png" width="300"/>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 4</strong>
    <audio src="resources/audios/r3-1-82.wav" controls></audio>
    <img src="resources/spectrograms/r3-1-82.png" width="300"/>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 5</strong>
    <audio src="resources/audios/r5-1-312.wav" controls></audio>
    <img src="resources/spectrograms/r5-1-312.png" width="300"/>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 6</strong>
    <audio src="resources/audios/r4-1-152.wav" controls></audio>
    <img src="resources/spectrograms/r4-1-152.png" width="300"/>
  </div>

</div>

---

## 2. Results from RAVE Model Training

### 2.1 Generated Samples from RAVE v2 Configuration+Prior (our preferred results)

---

### 2.2 Generated Samples from RAVE v2 Configuration

<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 1</strong>
    <audio src="resources/rave_v2/RAVE_V2_1.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 2</strong>
    <audio src="resources/rave_v2/RAVE_V2_2.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 3</strong>
    <audio src="resources/rave_v2/RAVE_V2_3.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 4</strong>
    <audio src="resources/rave_v2/RAVE_V2_4.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 5</strong>
    <audio src="resources/rave_v2/RAVE_V2_5.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 6</strong>
    <audio src="resources/rave_v2/RAVE_V2_6.wav" controls></audio>
  </div>

</div>

---

### 2.3 Generated Samples from RAVE v2-small Configuration

<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 1</strong>
    <audio src="resources/rave_v2_small/RAVE_V2_SMALL_1.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 2</strong>
    <audio src="resources/rave_v2_small/RAVE_V2_SMALL_2.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 3</strong>
    <audio src="resources/rave_v2_small/RAVE_V2_SMALL_3.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 4</strong>
    <audio src="resources/rave_v2_small/RAVE_V2_SMALL_4.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 5</strong>
    <audio src="resources/rave_v2_small/RAVE_V2_SMALL_5.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px;">
    <strong>Example 6</strong>
    <audio src="resources/rave_v2_small/RAVE_V2_SMALL_6.wav" controls></audio>
  </div>

</div>

---

### 2.4 Generated Samples from RAVE v1 Configuration

---

## 3. Results from StyleGAN2 Model Training
### 3.1 Generated Spectrograms → Audio Reconstruction → RAVE Correction

<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px; width: 300px;">
    <strong>Example 1</strong>
    <em>Generated Spectrogram</em>
    <img src="resources/stylegan_spectrograms/seed3312.png" width="300"/>
    <em>Reconstructed Audio</em>
    <audio src="resources/stylegan_no_correction/seed3312.wav" controls></audio>
    <em>RAVE-Corrected Audio</em>
    <audio src="resources/stylegan_rave/seed3312.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px; width: 300px;">
    <strong>Example 2</strong>
    <em>Generated Spectrogram</em>
    <img src="resources/stylegan_spectrograms/seed3313.png" width="300"/>
    <em>Reconstructed Audio</em>
    <audio src="resources/stylegan_no_correction/seed3313.wav" controls></audio>
    <em>RAVE-Corrected Audio</em>
    <audio src="resources/stylegan_rave/seed3313.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px; width: 300px;">
    <strong>Example 3</strong>
    <em>Generated Spectrogram</em>
    <img src="resources/stylegan_spectrograms/seed3325.png" width="300"/>
    <em>Reconstructed Audio</em>
    <audio src="resources/stylegan_no_correction/seed3325.wav" controls></audio>
    <em>RAVE-Corrected Audio</em>
    <audio src="resources/stylegan_rave/seed3325.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px; width: 300px;">
    <strong>Example 4</strong>
    <em>Generated Spectrogram</em>
    <img src="resources/stylegan_spectrograms/seed3358.png" width="300"/>
    <em>Reconstructed Audio</em>
    <audio src="resources/stylegan_no_correction/seed3358.wav" controls></audio>
    <em>RAVE-Corrected Audio</em>
    <audio src="resources/stylegan_rave/seed3358.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px; width: 300px;">
    <strong>Example 5</strong>
    <em>Generated Spectrogram</em>
    <img src="resources/stylegan_spectrograms/seed3360.png" width="300"/>
    <em>Reconstructed Audio</em>
    <audio src="resources/stylegan_no_correction/seed3360.wav" controls></audio>
    <em>RAVE-Corrected Audio</em>
    <audio src="resources/stylegan_rave/seed3360.wav" controls></audio>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 15px; width: 300px;">
    <strong>Example 6</strong>
    <em>Generated Spectrogram</em>
    <img src="resources/stylegan_spectrograms/seed14312.png" width="300"/>
    <em>Reconstructed Audio</em>
    <audio src="resources/stylegan_no_correction/seed14312.wav" controls></audio>
    <em>RAVE-Corrected Audio</em>
    <audio src="resources/stylegan_rave/seed14312.wav" controls></audio>
  </div>

</div>

---

### 3.2 StyleGAN2 Latent Space Interpolation

<div style="display: flex; flex-direction: column; gap: 40px;">

  <div style="display: flex; flex-direction: column; align-items: center; gap: 20px;">
    <video src="resources/stylegan_extended_video/sarir_stylegan2_interpolation.mp4" width="400" controls></video>
  </div>

</div>

---

### 3.3 Generated Samples Based on Latent Space Interpolation Using Concatenative algorithm

<div style="display: flex; flex-direction: column; gap: 40px;">

  <div style="display: flex; flex-direction: column; align-items: center; gap: 20px;">
    <strong>Example 1</strong>
    <audio src="resources/stylegan_extended/example_1.wav" controls></audio>
    <img src="resources/stylegan_extended_spectrograms/example_1.png" width="1200"/>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 20px;">
    <strong>Example 2</strong>
    <audio src="resources/stylegan_extended/example_2.wav" controls></audio>
    <img src="resources/stylegan_extended_spectrograms/example_2.png" width="1200"/>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 20px;">
    <strong>Example 3</strong>
    <audio src="resources/stylegan_extended/example_3.wav" controls></audio>
    <img src="resources/stylegan_extended_spectrograms/example_3.png" width="600"/>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 20px;">
    <strong>Example 4</strong>
    <audio src="resources/stylegan_extended/example_4.wav" controls></audio>
    <img src="resources/stylegan_extended_spectrograms/example_4.png" width="600"/>
  </div>

  <div style="display: flex; flex-direction: column; align-items: center; gap: 20px;">
    <strong>Example 5</strong>
    <audio src="resources/stylegan_extended/example_5.wav" controls></audio>
    <img src="resources/stylegan_extended_spectrograms/example_5.png" width="600"/>
  </div>

</div>

---

## 4. Results from Open-Source Text-to-Audio Models

<br>

<table style="border-collapse: collapse; width: 100%; text-align: center;">
  <tr style="border-bottom: 2px solid #ccc;">
    <th>Prompt</th>
    <th>AudioLDM2</th>
    <th>Stable Audio Open</th>
    <th>AudioGen</th>

  </tr>

  <tr style="border-bottom: 1px solid #ddd;">
    <td><em>"Arabic calligraphy sarir."</em></td>
    <td>
      <audio src="resources/audioldm2/Arabic calligraphy sarir..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/Arabic calligraphy sarir..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/Arabic calligraphy sarir..wav" controls></audio>
    </td>
  </tr>

  <tr style="border-bottom: 1px solid #ddd;">
    <td><em>"Persian calligraphy sarir."</em></td>
    <td>
      <audio src="resources/audioldm2/Persian calligraphy sarir..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/Persian calligraphy sarir..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/Persian calligraphy sarir..wav" controls></audio>
    </td>
  </tr>

  <tr style="border-bottom: 1px solid #ddd;">
    <td><em>"The creaking sound of a reed pen during Arabic calligraphy writing."</em></td>
    <td>
      <audio src="resources/audioldm2/The creaking sound of a reed pen during Arabic calligraphy writing..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/The creaking sound of a reed pen during Arabic calligraphy writing..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/The creaking sound of a reed pen during Arabic calligraphy writing..wav" controls></audio>
    </td>
  </tr>

  <tr style="border-bottom: 1px solid #ddd;">
    <td><em>"The creaking sound of a reed pen during Persian calligraphy writing."</em></td>
    <td>
      <audio src="resources/audioldm2/The creaking sound of a reed pen during Persian calligraphy writing..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/The creaking sound of a reed pen during Persian calligraphy writing..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/The creaking sound of a reed pen during Persian calligraphy writing..wav" controls></audio>
    </td>
  </tr>

  <tr style="border-bottom: 1px solid #ddd;">
    <td><em>"The sound of a reed pen writing in Arabic calligraphy."</em></td>
    <td>
      <audio src="resources/audioldm2/The sound of a reed pen writing in Arabic calligraphy..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/The sound of a reed pen writing in Arabic calligraphy..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/The sound of a reed pen writing in Arabic calligraphy..wav" controls></audio>
    </td>
  </tr>

  <tr style="border-bottom: 1px solid #ddd;">
    <td><em>"The sound of a reed pen writing in Persian calligraphy."</em></td>
    <td>
      <audio src="resources/audioldm2/The sound of a reed pen writing in Persian calligraphy..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/The sound of a reed pen writing in Persian calligraphy..wav" controls></audio>
    </td>
    <td>
      <audio src="resources/audioldm2/The sound of a reed pen writing in Persian calligraphy..wav" controls></audio>
    </td>
  </tr>

</table>
