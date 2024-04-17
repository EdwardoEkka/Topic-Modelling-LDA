
# YouTube Data Analysis with LDA Topic Modeling

This script allows you to perform topic modeling on YouTube video titles and analyze trends in likes over time for each identified topic. Follow the steps below to test your YouTube data:

## Step 1: Requirements

Make sure you have the following installed:

- Python 3.x
- Required Python packages:
  - pandas
  - nltk
  - scikit-learn
  - matplotlib

You can install these packages using pip:

```
pip install pandas nltk scikit-learn matplotlib
```

## Step 2: Prepare Your Data

Format your YouTube data into a JSON file with the following structure:

```json
[
    {
        "title": "Your video title 1",
        "likes": 100,
        "publishedAt": "YYYY-MM-DDTHH:MM:SSZ"
    },
    {
        "title": "Your video title 2",
        "likes": 200,
        "publishedAt": "YYYY-MM-DDTHH:MM:SSZ"
    },
    ...
]
```

Save this file as `data_youtube.json`.

## Step 3: Customize Stop Words (Optional)

If you want to customize the stop words used for tokenization, you can edit the `stop_words` list in the script. Add or remove words based on your requirements.

```python
stop_words = [
    'for', 'couldn', 'hers', 'so', 'myself', 'themselves', 'each',
    ...
]
```

## Step 4: Run the Script

Run the script `youtube_analysis.py` using the following command:

```
python youtube_analysis.py
```

## Step 5: Analyze Results

After running the script, you'll get the following outputs:

- Topic modeling results printed in the console.
- Trend analysis plots for each topic displayed in separate windows.
- A JSON file named `youtube_model.json` containing the topics and titles in each topic.

## Step 6: Customize Analysis Parameters (Optional)

If you want to customize the analysis further, you can modify the following parameters in the script:

- **Number of Topics**: Adjust the `num_topics` variable to change the number of topics identified by the LDA model.

```python
num_topics = 5
```

## Step 7: Run the Script

After making the necessary changes, run the script using the command line or any Python environment:

```bash
python youtube_analysis.py
```

## Step 8: Analyze Results

After running the script, you'll get the following outputs:

- Topic modeling results printed in the console.
- Trend analysis plots for each topic displayed in separate windows.
- A JSON file named `youtube_model.json` containing the topics and titles in each topic.

Feel free to explore and analyze the results further!

---

You can add more details or customize the instructions based on your preferences and the specifics of your script.
