# Hybrid HGNN-BiLSTM Model for Cryptocurrency Price Prediction

## Description
A novel hybrid approach combining Hierarchical Graph Neural Network (HGNN) and Bidirectional LSTM for cryptocurrency price prediction, with a focus on Bitcoin (BTC). This model leverages both graph-based market relationships and temporal sequence patterns for enhanced prediction accuracy.

## Model Architecture

### HGNN Component
- Utilizes GCNConv layers for processing graph-based market data
- Captures market relationships and hierarchical patterns
- Processes market structure through graph representations
- Extracts features from market relationship patterns

### Bi-LSTM Component
- Dual LSTM architecture for bidirectional temporal processing
- Processes time series data in both forward and backward directions
- Captures long-term dependencies in price movements
- Combines temporal information from both directions

### Hybrid Integration
- Fusion of graph-based and temporal features
- Combined prediction mechanism
- Integrated training pipeline
- Joint feature extraction and analysis

## Requirements
```
torch
torch_geometric
pandas
numpy
scikit-learn
matplotlib
```

## Features
- Hierarchical market structure analysis
- Bidirectional temporal pattern recognition
- Combined feature extraction
- Integrated prediction pipeline
- Market relationship modeling
- Time series analysis

## Data Processing
1. Market data extraction and preprocessing
2. Graph construction for HGNN
3. Time series preparation for Bi-LSTM
4. Feature engineering and normalization

## Model Training
- Joint training of HGNN and Bi-LSTM components
- Custom loss function for combined prediction
- Optimization strategy for dual architecture
- Validation and testing procedures

## Results
- Performance metrics for both components
- Combined model accuracy
- Comparison with individual models
- Trading strategy evaluation

## Implementation Details
- GCNConv for graph processing
- Dual LSTM layers for temporal analysis
- Feature fusion mechanism
- Custom training pipeline

## Future Improvements
- Enhanced feature integration
- Additional market indicators
- Real-time prediction capabilities
- Advanced optimization techniques

## Authors
[Soroush Azizi]

## Acknowledgments
- Original HGNN paper and implementation
- Bi-LSTM architecture references
- Cryptocurrency market data sources
