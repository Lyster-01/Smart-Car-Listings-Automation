# Smart-Car-Listings-Automation

This workflow is a scheduled web scraping and data logging pipeline. It automatically extracts car listing details from a dealership website and stores them in a structured format for tracking and analysis.

It starts with a Schedule Trigger, which runs the workflow automatically every Monday at 9 AM. This ensures that the data collection happens consistently without any manual intervention.

Next, an HTTP Request node sends a GET request to the Magari Deals website, retrieving the raw HTML content of the car listings page.