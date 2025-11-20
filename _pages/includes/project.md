# 🚀 Project Experience
## 2025.09 - 2025.11     Research on Composite Material 3D Printing Performance Prediction Based on Large Language Models
### Project Background: 
Current mainstream cloud-based large language models perform poorly in the field of 3D printing material-structure-performance prediction. To use AI agents to improve research efficiency in this field, extensively collected vertical domain data from temporal and spatial dimensions. Developed an expert-level language model adapted to this field through model fine-tuning and Retrieval-Augmented Generation (RAG), achieving precise and efficient material-structure-performance prediction.
### Model Pre-training & Fine-tuning: 
Built and pre-trained (Pre-Train), supervised fine-tuned (SFT), and reinforced learned (RL) the model from scratch based on open-source on-device small language model frameworks. Conducted LoRA fine-tuning on the model using a self-built vertical domain knowledge base to enhance domain adaptability. Fine-tuned Qwen using LLaMa-Factory, ultimately achieving the effect of an expert language model with excellent performance.
### RAG Workflow Construction: 
Disassembled the full-process working logic of the expert language model, and built a standardized RAG workflow adapted to the 3D printing material-structure-performance prediction scenario based on Dify tools. Achieved context enhancement by retrieving the self-built vertical domain knowledge base, enabling efficient and accurate system responses in professional scenarios.

## 2025.09 - 2025.10     Stock Price Prediction Model Based on Long Short-Term Memory (LSTM) Networks
### Project Content: 
Participated in the weekly closing price prediction of 10 Hong Kong-listed stocks (including Tencent, Alibaba, SMIC, etc.). Responsible for stock volatility classification, multi-model development, and full-cycle iterative optimization, supporting core links from solution design to implementation.
### Solution Design & Data Processing: 
Classified stocks into high volatility (σ≥1.5%) and low volatility (σ<1.5%) based on the standard deviation of returns over 500 trading days. Designed a dual-track prediction framework to match models of different complexities, balancing fitting degree and interpretability.
### Model Development & Optimization: 
Built and iterated linear regression, LSTM, and sentiment-enhanced LSTM models (integrating 4 types of sentiment indicators such as turnover rate and VIX index) for stock price prediction. Completed multiple rounds of model iteration within 5 weeks, optimized defects through MAPE (Mean Absolute Percentage Error) and prediction error analysis. Ultimately achieved a test set MAPE as low as 1%-3%, and an average MAPE of 5% in practical performance, with significant improvements in accuracy and stability.
