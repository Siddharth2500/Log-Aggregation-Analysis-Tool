# Log-Aggregation-Analysis-Tool

<img width="1789" height="1180" alt="image" src="https://github.com/user-attachments/assets/59db5267-892b-4920-8127-577b44cca3ae" />


### Description
Advanced log analysis system that aggregates logs from multiple sources, performs pattern recognition, identifies anomalies, and generates insights with ML-based predictions.

### Features
- Multi-source log aggregation
- Pattern recognition and clustering
- Anomaly detection
- Error rate tracking
- Log level distribution analysis
- Search and filter capabilities

### Tech Stack
- Python 3.8+
- Regular expressions for parsing
- Pandas for data manipulation
- Scikit-learn for ML analysis
- Matplotlib for visualization

### Installation
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
python log_analyzer.py
```

### Usage
```python
# Aggregate and analyze logs
analyzer = LogAnalyzer()
analyzer.add_log_source("/var/log/app.log")
analyzer.analyze_patterns()
analyzer.detect_anomalies()
```

### Output
- Log pattern frequency charts
- Error rate trends
- Anomaly detection graphs
- Time-series analysis

---
