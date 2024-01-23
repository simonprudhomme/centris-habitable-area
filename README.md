# Project Description

This project provides tools to efficiently parse Centris real estate listings for the purpose of calculating the average price per square foot of a property. Leveraging OCR (Optical Character Recognition) technology, the tool automates the extraction and analysis of room dimensions from property listings. This enables users to gain quick insights into property value based on area.

## Features
- **Automated Room Dimension Parsing:** Process screenshots of property listings, extracting room dimensions using advanced OCR techniques.
- **Area Calculation:** Automatically calculate the total area of each room and the entire property.
- **Price Per Square Foot Analysis:** Evaluate and display the price per square foot, offering a clear measure of the property's value.

## Workflow
1. **Capture Property Data:** Take a screenshot of the room dimensions from a Centris property listing.
2. **Data Preparation:** Copy the screenshot image into the `data/` folder.
3. **Automated Processing:** The tool processes the image, calculates the total area of the rooms, and computes the price per square foot.

## Installation Instructions
Follow these steps to set up the project environment:

1. **Clone the Repository:**
   ```bash
   git clone [repository-link]
2. **Create virtual environments and install dependancies:**
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. **Create .env and add OPENAI_API_KEY:**
   ```bash
    touch .env

    # Add the following to .env:
    # OPENAI_API_KEY=<your api key>
    ```
