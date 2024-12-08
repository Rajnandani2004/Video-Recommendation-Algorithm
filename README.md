# Video-Recommendation-Algorithm

**Overview**  
This project demonstrates the creation of a recommendation system using user interaction data and content information. The goal is to provide personalized content suggestions by implementing collaborative filtering, content-based filtering, and a hybrid model combining the two.  

**Features**  
- **Collaborative Filtering**: Recommends posts based on user behavior similarity using interaction data (views, likes, inspirations, and ratings).  
- **Content-Based Filtering**: Suggests posts with similar categories or content types to what the user has interacted with.  
- **Hybrid Model**: Combines collaborative and content-based approaches to deliver the most relevant and diverse recommendations.  

**Data Sources**  
The system uses data retrieved from API endpoints, including:  
1. **Posts**: Details about each post (e.g., title, category, rating).  
2. **Users**: User profiles and details.  
3. **User Interactions**: Data on views, likes, inspirations, and ratings provided by users on posts.  

**How It Works**  
1. User interaction data is combined into a single dataset and converted into an interaction matrix.  
2. Collaborative filtering calculates user similarities using cosine similarity and suggests posts liked by similar users.  
3. Content-based filtering identifies similar posts based on their category.  
4. The hybrid model merges these recommendations for better accuracy and variety.  

**Outcome**  
The recommendation system effectively identifies and suggests posts that match user preferences, improving user engagement and content discovery.  

**Conclusion**  
This project highlights the importance of combining user data and content analysis to build a robust recommendation system, showcasing the power of data-driven personalization.
