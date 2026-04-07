# 🌱 AI-Based Plant Growth Simulator

An AI-driven plant growth simulation system that models plant development using DNA sequence features, environmental data, and Graph Neural Networks (GNNs).

This project demonstrates how bioinformatics, machine learning, and environmental modeling can be combined to simulate plant growth and visualize plant evolution over time.

The simulator acts as a simplified digital twin of a plant, integrating genomic signals and climate conditions to generate dynamic plant traits.

---

## 🎯 Project Objectives

The main goals of this project are:

- Extract biological signals from DNA sequences  
- Integrate environmental climate data  
- Model gene interactions using Graph Neural Networks  
- Simulate plant growth dynamics over time  
- Visualize plant development and trait evolution  
- Demonstrate an AI-powered digital twin approach for plant systems  

---

## 🧠 Scientific & AI Concepts

This project combines concepts from several scientific domains:

- 🧬 Bioinformatics  
- 🤖 Machine Learning  
- 🌱 Computational Biology  

### Key techniques used:

- DNA feature extraction (k-mer frequencies)  
- Gene regulatory network modeling  
- Graph Neural Networks (GNN / GCN)  
- Time-series simulation  
- Environmental data integration  
- Scientific visualization  

---

## 🧬 Biological Data

The simulation uses genomic information from the model plant:

**Arabidopsis thaliana**

DNA sequences are retrieved from:

- National Center for Biotechnology Information (NCBI)

The DNA sequence is transformed into numerical features using k-mer frequency extraction.

### Example extracted features:

- AT frequency  
- CG frequency  
- GC frequency  

These features represent simplified genomic signals influencing plant growth behavior.

---

## 🌍 Environmental Data

Environmental conditions are retrieved from:

- Open-Meteo

### Climate variables used in the simulation:

- Temperature  
- Humidity  
- Sunlight  

These variables affect plant growth dynamics in the simulation model.

---

## 🧠 AI Model

The project uses a **Graph Convolutional Network (GCN)** to simulate gene interactions within a gene regulatory network.

### In this network:

- Nodes represent genes  
- Edges represent regulatory relationships between genes  

The neural network processes the gene graph and produces a gene activity signal, which influences the plant growth rate during the simulation.

---

## 🌱 Plant Growth Simulation

Plant development is simulated over time using:

- Genomic features  
- Environmental conditions  
- AI-generated gene activity signals  

### The simulation produces dynamic plant traits such as:

- Plant height  
- Leaf count  
- Root depth  
- Stem thickness  
- Biomass accumulation  
- Canopy width  
- Flowering probability  
- Water stress level  
- Plant health index  

---

## 📊 Visualization

The notebook generates several visual outputs:

- 📈 Growth curves  
- 📊 Trait evolution plots  
- 🌿 Simplified 2D plant visualization  

These visualizations allow observation of plant development over time.

---

## 🏗 Project Workflow

The notebook follows this pipeline:

1. DNA sequence retrieval  
2. DNA feature extraction (k-mers)  
3. Gene regulatory network construction  
4. Graph Neural Network processing  
5. Climate data retrieval  
6. Plant growth simulation  
7. Trait generation  
8. Visualization of plant evolution  

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/TLIBA-Ahmed/plant-growth-simulator.git
cd plant-growth-simulator
