# Polar Codes – CT216 Project Report (Group 31)

Welcome to the documentation repository for our academic project on **Polar Codes**, submitted as part of the *CT216 - Introduction to Communication Systems* course at Dhirubhai Ambani Institute of Information and Communication Technology (DAIICT).

---

## 📚 Overview

Polar Codes, introduced by Erdal Arıkan in 2009, are the first provably capacity-achieving error-correcting codes for symmetric binary-input memoryless channels. This project provides a detailed study on:

- Channel Polarization
- Polar Encoding and Decoding
- Bhattacharyya Parameter and Reliability Estimation
- Successive Cancellation and List Decoding
- Shannon Capacity Derivation
- Advanced decoding optimizations including:
- Large-small sorting
- Reed-Muller code identification

---

## 🧠 Topics Covered

### 1. **Introduction to Polar Codes**
- Definition and motivation
- Use in 5G and NASA communication systems

### 2. **Channel Polarization**
- Channel combining and splitting
- Bhattacharyya parameter for channel reliability

### 3. **Encoding Mechanisms**
- Matrix-based encoding using Kronecker products
- Tree-based encoding approach
- Time complexity comparisons: `O(N^2)` vs `O(N log N)`

### 4. **Decoding Techniques**
- **Successive Cancellation (SC) Decoding**
- **Successive Cancellation List (SCL) Decoding**
- **CRC-Aided SCL (CA-SCL) Decoding**
- Detailed walkthrough of min-sum and g-function logic
- Complexity and limitations of SC and benefits of SCL

### 5. **Simulations**
- BER/BLER performance of Polar Codes under SC and SCL decoders
- Comparative analysis with uncoded AWGN channels

### 6. **Shannon Capacity**
- Mathematical derivation showing how Polar Codes approach channel capacity
- Polar transform and mutual information properties

### 7. **Decoding Optimization**
- Reed-Muller code blocks integration
- Latency and performance improvements with hybrid decoders

### 8. **Large-Small Sorting**
- An efficient pruning method in SCL decoding
- Reduces computational complexity by avoiding unnecessary comparisons
- Selects the most reliable L candidates from 2L child paths using metric transitivity
- Useful in hardware-efficient implementations and low-latency applications

---

## 📊 Simulations

The report includes various plots comparing Polar Codes' bit error performance across:
- Block lengths: 32, 256, 512, 1024
- Decoding strategies: SC vs SCL
- Noise environments: AWGN, Laplace, Uniform

---

## 👨‍🏫 Contributors – Group 31

- Yuva Undaviya
- Aalok Thakkar
- Jay Manishkumar
- Jas Mehta
- Dhruvil Katharotiya
- Vrajkumar Makwana
- Maanav Gurubaxani
- Vraj Parikh
- Hrithik Patel
- Shubham Ramoliya

**Mentor:** Dharmi Patel  
**Professor:** Yash Vasavada

---

## 📄 References

The report references foundational works by:
- E. Arıkan (original polar codes paper)
- Shannon’s Channel Capacity Theorem
- Modern optimizations from IEEE papers and arXiv preprints

A full list of citations is included in the original PDF report
