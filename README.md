Wildfire Risk Assessment Model (WRAM) 
The Wildfire Risk Assessment Model (WRAM) leverages AI and satellite data to identify high-risk wildfire areas, helping local governments, firefighters, and communities take preventive action. Using Sentinel-2 satellite images, WRAM breaks down pre-fire images into 12 spectral bands, enabling our model to analyze green light, moisture, and other indicators to detect areas most vulnerable to wildfires.

Key Features
Data Source: Sentinel-2 satellite images segmented into spectral bands.
AI Model: U-Net-based CNN for high-resolution image segmentation, identifying areas at risk of wildfires.
Model Training: 80% training data, with dropout regularization and data augmentation to improve performance.
Validation: Risk prediction masks are compared against “ground truth” wildfire data from the California Department of Forestry and Fire Protection.
Future Goals: Integrate real-time data (e.g., wind speed, humidity), scale for larger regions, and create a public-facing interface and API.
Results & Community Outreach
Our model achieves accurate predictions, validated against historical fire data, and plans to partner with local agencies to implement WRAM in fire prevention strategies. Community workshops will empower officials to use the model for improved fire risk management.

Future Enhancements
Add more data sources: Real-time environmental data.
Expand model usability: APIs, cloud-based monitoring, and post-fire recovery assessment tools.
