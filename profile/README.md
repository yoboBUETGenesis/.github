# ShopGenie

## Motivation
ShopGenie is an AI powered market-place where you can find any product easily. You don't need to know about the brand, the shop or any detail. Just tell us how the product is like and BAM! You will see it before your eyes. We enable multimodal searching features. You can search with text, image or voice. You can use more than one searching feature at the same time. Maybe in image, you give a shirt and in text you may write, 'I want the same shirt but in blue color'. And then you will see the magic. Also we have recommendation model based on your preference. Last but not the least, we have sentiment-analysis on product review

## Main Features
> Multimodal search <br>
> Vector-DB integration <br>
> Sentiment Analysis <br>
> Recommendation System

## Tech-Stack
> OpenAI (for generating embedding and filtering the most relevant products) <br>
> Qdrant (for hosting the vector database on cloud) <br>
> Gemini (for analyzing query image) <br>
> Roboflow (for using api service of CLIP-VIT-B-32 model) <br>
> Sveltekit (as Meta framework) <br>
> Supabase (for database) <br>
> Beautiful Soup for web scraping <br>

## Flow of project
> We scraped product list from different famous shopping sites like Aarong, Allen-solly, Infinity, Apex ... <br>
> Check out The entire dataset from [here](https://huggingface.co/datasets/Melikshah/products)<br>
> We created vector database and hosted in Qdrant <br>
> The UI part <br>
> Individual repositories contain details

