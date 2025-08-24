# 🖼️ Digital Image Restoration Techniques  

This project explores **digital image restoration methods** to recover images degraded by noise and blur. It implements filtering techniques such as **Inverse Filtering**, **Wiener Filtering**, and an **Enhanced Recursive Median Filter (ERMF)** to handle impulse noise (salt-and-pepper) and motion blur.  

---

## 📌 Features
- Implementation of **motion blur degradation** using adjustable parameters.  
- Addition of **Gaussian noise** and **salt-and-pepper noise** to simulate real-world conditions.  
- Restoration using:
  - **Inverse Filtering** (effective in noise-free conditions).  
  - **Wiener Filtering** (handles both blur and noise adaptively).  
  - **Modified Recursive Median Filter (MRMF)** for high-density impulse noise.  
- Comparative analysis of different filtering approaches.  
- Visualization of results for various noise densities (40% – 80%).  

---

## ⚙️ Techniques Used
- **Inverse Filtering** → Effective for deblurring when no noise is present.  
- **Wiener Filtering** → Balances noise suppression and detail preservation.  
- **Median Filtering** → Removes salt-and-pepper noise while preserving edges.  
- **Modified Recursive Median Filter (MRMF)** → Adaptive filtering based on uncertainty modeling.  
- **Morphological Operations** → Helps reduce isolated noise points.  

---
📊 Results

Inverse Filtering: Works well without noise but degrades in noisy conditions.

Wiener Filtering: Restores motion-blurred images effectively, even with added noise.

MRMF: Outperforms standard median filter at higher noise levels, preserving edges and structures.


📖 Applications

Medical imaging (MRI, CT scans)

Satellite and astronomical imaging

Surveillance and forensic video enhancement

Media and photography post-processing


👨‍💻 Contributors

Honey Bohra – SVNIT Surat

Chanugonipalli Vaishnavi – SVNIT Surat

Kolli Yaswanth – SVNIT Surat

