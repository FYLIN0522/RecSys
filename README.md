## Description
Application of the Apriori and Cosine Similarity algorithms to recommend games on the Steam platform. Analyze and compare the similarity of tags from games recommended by these algorithms to the tags of games that users frequently play. 

## Datasets
The study uses the following datasets from UCSD(https://cseweb.ucsd.edu/~jmcauley/datasets.html):
- `Australian_users_items`: User game inventories and gameplay statistics.
- `Steam_games`: Information on games including names, tags, and specifications.

## Methods
- **Data Preparation**: Data from the UCSD datasets is preprocessed and transformed into a suitable format.
- **Apriori Algorithm**: Used to identify sets of frequently co-occurring games within user data.
- **Cosine Similarity Algorithm**: Used to find games with similar tags to those the user frequently engages with.

## Usage
Import to google collab and run.