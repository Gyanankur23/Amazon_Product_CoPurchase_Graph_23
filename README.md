# Amazon_Product_CoPurchase_Graph_23 CaseCraft Analytics Project Sprint Project 23

## 🛒 Overview  
This project models Amazon’s co-purchase behavior using network graphs, centrality metrics, and clustering. It uncovers product relationships that drive bundling, upselling, and recommendation strategies.

## 🎯 Objective  
To simulate a co-purchase graph, analyze its structure, and extract strategic insights for cross-selling and affinity-based recommendations.

## 🧩 Dataset & Graph Construction  
- Products: 50 synthetic SKUs (`P1` to `P50`)  
- Edges: 300 co-purchase links with weights (frequency)  
- Graph Type: Undirected, weighted  
- Tools: NetworkX, Pandas, Matplotlib

## 📊 Visual Explorations  
- **Histogram**: Co-purchase edge weights  
- **Spring Layout Graph**: Full network visualization  
- **Bar Charts**: Top 10 products by degree & betweenness centrality  
- **Heatmap**: Co-purchase frequency matrix  
- **Bar Chart**: Most frequent product pairs  
- **Heatmap**: Product feature correlations (price, rating, reviews)

## 📈 Network Metrics  
- **Density**: 0.222  
- **Largest Connected Component**: 50 nodes (100% coverage)  
- **Top Nodes**:  
  - Degree Centrality: P12, P27, P40  
  - Betweenness Centrality: P21, P35, P50

## 🧠 Key Insights  
1. **Strong Connectivity**: Most products are part of a single, dense component  
2. **Anchor Products**: High centrality nodes ideal for bundling and promotions  
3. **Bridging Nodes**: Betweenness centrality reveals cross-category connectors  
4. **Affinity Clusters**: Frequent pairs suggest natural bundles (e.g., P13–P33)  
5. **Feature Correlation**: Price and reviews show moderate alignment  
6. **Strategic Leverage**: Graph structure supports scalable recommendation logic

## ✅ Final Conclusion  
Amazon’s co-purchase graph reveals rich structural patterns. Centrality metrics identify anchor products, while heatmaps and pair frequencies guide affinity-based bundling. This network approach enables scalable upselling and cross-category promotion strategies.