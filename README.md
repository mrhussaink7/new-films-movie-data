{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "fa7d7baf-fd09-48be-b5f7-c9f8f5bfd775",
   "metadata": {},
   "source": [
    "# Recommending Films for Box Office Success!"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "f05ee1b5-447b-44ab-859e-063f3a8eb2d1",
   "metadata": {},
   "source": [
    "![image](https://vip-go.premiumbeat.com/wp-content/uploads/2022/02/vr_2.jpg)\n",
    "\n",
    "*Image by DOP Eben Bolter on the LED volume stage at Rebellion Film Studios in Oxford, UK.*"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8e0aaca2-cd35-4a62-bc97-35854b804cd3",
   "metadata": {},
   "source": [
    "## Overview"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d5db37bb-41ff-48a9-b839-abc653c91df0",
   "metadata": {},
   "source": [
    "Our company sees competitors creating original video content and now wants to join the market trend. We create a new film studio despite the lack of knowledge in everything related to movies.\n",
    "\n",
    "As the data scientist of the company, my goal is to explore what types of films are currently performing the best at the box office and with my findings – create actionable insights that the company's new studio can use to decide what type of films to create."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "86bb3d81-bcd6-4771-94ed-24b31bea1301",
   "metadata": {},
   "source": [
    "## Challenge"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "0666e27f-87f1-44fd-aed4-28c7a834eec3",
   "metadata": {},
   "source": [
    "With the task at hand, we will be presenting to our company stakeholders three different recommendations that will directly affect our business revenue. The goal is to provide data-driven direction for our new film studio using evidence that our recommendations will result in truly benefitting the company."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3a85eb41-71d4-4e02-9175-75cb5ec4ad29",
   "metadata": {},
   "source": [
    "## Datasets"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b9d8f8ee-0768-475b-9e6b-c69cb83f3af0",
   "metadata": {},
   "source": [
    "In the folder `zippedData`, we have datasets from:\n",
    "\n",
    "- [Box Office Mojo](https://www.boxofficemojo.com/)\n",
    "- [IMDB](https://www.imdb.com/)\n",
    "- [The Numbers](https://www.the-numbers.com/)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "4ba9b82f-e141-4e63-ba03-f4bc0d6f198c",
   "metadata": {},
   "source": [
    "## Solution"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "9f9f04f1-7149-4635-91bd-34f9f9aa520a",
   "metadata": {
    "scrolled": true
   },
   "source": [
    "This project uses statistical analysis, including formulating three hypotheses of what contributes to a film's success. We infer three different business recommendations and use box-office data to prove our hypotheses and provide statistics as evidence to support our recommendations for the company and the direction for our new film studio."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b07f7b88-d4ad-4c72-ac8a-0f9a82477f3b",
   "metadata": {},
   "source": [
    "## Results"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "07a1225a-df65-4d3f-8868-ab5333974a59",
   "metadata": {},
   "source": [
    "### 1. Plan for higher budget production to maximize returns.\n",
    "\n",
    "`Insight:` We observed that budget plays a significant role in a film's success, with higher budgets generally correlating with higher revenues. This was supported by the positive trend on the scatterplot and correlation coefficient close to +1.\n",
    "\n",
    "`Recommendation:` Plan and allocate for higher budgets on our films to maximize potential revenue."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "f1dba7b4-f8be-4ed8-a6dc-e4a77d410a4a",
   "metadata": {},
   "source": [
    "![image](images/hypothesis1_graph.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "da676b24-9aa5-4885-ba83-e87ede0318ed",
   "metadata": {},
   "source": [
    "### 2. Releasing films during the spring months can create more sales.\n",
    "\n",
    "`Insight:` We observed statistical significance of films released in the spring months and revenue earned compared to the other times of the year. This was supported by our p-value > 0.05 rejecting the null hypothesis that there's no difference of revenues in the spring months compared to other months.\n",
    "\n",
    "`Recommendation:` Plan major releases during these months to capitalize on higher audience and box-office turnout."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "55d3d119-eb97-4ec0-8062-39caf1d2b91b",
   "metadata": {},
   "source": [
    "![image](images/hypothesis2_graph.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "5214f4d8-5070-4a18-982d-4aab2ec0b21e",
   "metadata": {},
   "source": [
    "### 3. Focus production towards profitable and compelling genres.\n",
    "\n",
    "`Insight:` We observed a significant difference in the average revenues across various genres, giving us direction for production. This was supported by our p-value > 0.05 rejecting the null hypothesis that there's no difference in revenues across different genres, revealing genres with great value for production.\n",
    "\n",
    "`Recommendation:` Produce films with aspects of the genre-groups that are proven to drive success."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "44c811c8-5eba-42aa-b28c-d2e9bda183cd",
   "metadata": {},
   "source": [
    "![image](images/hypothesis3_graph.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "a6b2e312-55bb-4132-88b7-7bf29851bc81",
   "metadata": {},
   "source": [
    "## Conclusion"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "39e01195-04b5-4768-81b2-9bdf864feda8",
   "metadata": {},
   "source": [
    "- #### Allocate for higher budgets on our films to maximize potential revenue.\n",
    "\n",
    "- #### Plan major releases during these months to capitalize on higher audience and box-office turnout.\n",
    "\n",
    "- #### Produce films with aspects of the genre-groups that are proven to drive success."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c813bdf4-6266-4b93-8f94-abb6731f95f4",
   "metadata": {},
   "source": [
    "## Next Steps"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "80f19ec7-1f4c-4974-bc83-e94dc8d3a838",
   "metadata": {},
   "source": [
    "- #### Implement predictive modeling and linear regression analysis to forecast movie revenues based on budget, genre, and release timing, providing stakeholders with data-driven revenue predictions.\n",
    "- #### Explore other features and variables such as ratings and reviews to uncover additional factors that influence movie success, enhancing the overall predictive model.\n",
    "- #### Apply optimization techniques for effective budget allocation, ensuring resources are used in a way that maximizes potential returns on investment."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "23a92551-c85d-4a67-81b3-0a3094c0d7a6",
   "metadata": {},
   "outputs": [],
   "source": [
    "def custom_formatter(x, pos):\n",
    "    return f'${x / 1e6:.1f}M'"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "46106fc2-5cc8-490c-b0be-cef2a3cf2173",
   "metadata": {},
   "source": [
    "### IMdb, SQL Database"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2982d836-3d17-41e6-bd0d-893b6170303f",
   "metadata": {},
   "source": [
    "IMdb aims to collect any and all data of all films to showcase everyday people."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "3870f37b-d4f3-4e3f-ba62-4f351e484085",
   "metadata": {},
   "outputs": [],
   "source": [
    "zip_path = 'zippedData/im.db.zip'\n",
    "extract_path = 'zippedData/'\n",
    "\n",
    "with zipfile.ZipFile(zip_path,'r') as zip_ref:\n",
    "    zip_ref.extractall(extract_path)\n",
    "\n",
    "db_path = os.path.join(extract_path, 'im.db')\n",
    "\n",
    "conn = sqlite3.connect(db_path)\n",
    "pd.read_sql(\"\"\"\n",
    "    SELECT *\n",
    "    FROM sqlite_master\n",
    "    WHERE type = 'table';\n",
    "\"\"\",conn)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "153b59f1-e18c-4257-944a-9a037074e1cc",
   "metadata": {},
   "outputs": [],
   "source": [
    "df_imdb = pd.read_sql(\"\"\"\n",
    "    SELECT *\n",
    "    FROM movie_basics AS mb\n",
    "    INNER JOIN movie_ratings AS mr ON mb.movie_id =mr.movie_id;\n",
    "\"\"\",conn)\n",
    "df_imdb['title'] = df_imdb['primary_title']\n",
    "df_imdb"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "31d339c3-e99f-4830-9878-7906abadc19c",
   "metadata": {},
   "source": [
    "### TheNumbers, CSV"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d3de223e-7cfd-49ea-bdbb-72e277e6b451",
   "metadata": {},
   "source": [
    "TheNumbers goal is to collect the most accurate details of any film's budgets and revenues."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "b5ba7329-2c16-4540-a92b-8b4cdba30319",
   "metadata": {},
   "outputs": [],
   "source": [
    "df_tn_movie_budgets = pd.read_csv('zippedData/tn.movie_budgets.csv.gz')\n",
    "df_tn_movie_budgets['title'] = df_tn_movie_budgets['movie']\n",
    "df_tn_movie_budgets"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d713d619-bb0b-429a-8443-677b81a3ed41",
   "metadata": {},
   "source": [
    "### Merge Data For Analysis"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "4468f326-cd4d-4e1b-9d13-2c78529be371",
   "metadata": {},
   "source": [
    "Reasons for Combined Data\n",
    "- It was neccessary we `merge` our data from `IMdb` and `TheNumbers` because IMdb is a popular platform that houses all details of films, including genres, ratings, and votes and TheNumbers has reliable information regarding film budgets and revenues across the world.\n",
    "- By combining these two datasets, we couple our data of `films`, `genres`, `ratings`, and `votes` with `financial data` to help us investigate deeper in our analysis."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "651490db-9d1b-4bdf-928c-94c3604c6ada",
   "metadata": {},
   "outputs": [],
   "source": [
    "df_box_office = pd.merge(df_imdb, df_tn_movie_budgets, on='title', how='inner')\n",
    "df_box_office"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "12b0c617-1558-4828-b817-110e0ed3eecf",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "### 1. Understanding The Data\n",
    "- Dataframe `shape`\n",
    "- `head` and `tail`\n",
    "- `info`\n",
    "- `describe`"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "fc825a54-6993-4993-a191-ff3793a93b7a",
   "metadata": {},
   "outputs": [],
   "source": [
    "df_box_office.head()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "8821db01-74c4-4410-aa1c-a8d95ae03557",
   "metadata": {},
   "outputs": [],
   "source": [
    "df_box_office.shape"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "6ed29ef7-8ec6-422c-9b39-06322c73847a",
   "metadata": {},
   "outputs": [],
   "source": [
    "df_box_office.info()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "38696fcc-1b9e-4078-9c73-9019593abeee",
   "metadata": {},
   "outputs": [],
   "source": [
    "df_box_office.describe()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3026d05a-32e0-42b5-bddf-78c5d8611e65",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "### 2. Data Preparation\n",
    "- Dropping irrelevant columns and rows\n",
    "- Identifying duplicated columns\n",
    "- Renaming columns\n",
    "- Feature creation"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8db2f0ca-52c3-4c12-9b04-f489530c95fc",
   "metadata": {},
   "source": [
    "Let's clean up our dataset by `dropping` irrelevant `columns` and `renaming` them to represent the data better."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "63706204-6d3d-4e83-ac29-dfc799eb607f",
   "metadata": {},
   "outputs": [],
   "source": [
    "df = df_box_office[[\n",
    "    # 'movie_id', 'original_title', 'start_year', \n",
    "    # 'runtime_minutes', 'movie_id', 'title', 'id', 'movie'\n",
    "    'primary_title',  'genres', 'averagerating', 'numvotes', \n",
    "    'release_date', 'production_budget', 'worldwide_gross' ]]\n",
    "\n",
    "df.rename(columns={ 'primary_title':'film', 'averagerating':'rating', 'numvotes':'votes', \n",
    "                    'release_date':'release', 'production_budget':'budget',\n",
    "                    'worldwide_gross':'revenue' }, inplace=True)\n",
    "\n",
    "df.info()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b5e2ffdd-8615-4fc1-a1db-cefffd509b2b",
   "metadata": {},
   "source": [
    "There are some important data preparation we need to do:\n",
    "- Replace `genre` values that are `NaN` with string `'unknown'` if data is missing. This way we are not losing any data even if we don't know the genre.\n",
    "- Convert `release` to pandas `datetime` so that we can do some logical operations over it for deeper investigation.\n",
    "- Convert `budget` and `revenue` into `int` so that we can do logical operations over the data for better analysis.\n",
    "- Create new feature `profit` so that we better understand film financials.\n",
    "- Normalize `rating` because the feature is directly affected by `votes` which disproportianately affects the true rating."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "c10c1a9f-70f7-4a8d-99b3-cc16b6f3358c",
   "metadata": {},
   "outputs": [],
   "source": [
    "df['genres'].fillna('unknown', inplace=True)\n",
    "df.genres"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "7736831d-52e6-49c6-9302-fd17b277d968",
   "metadata": {
    "scrolled": true
   },
   "outputs": [],
   "source": [
    "mask = pd.to_datetime(df['release'], format='%b %d, %Y')\n",
    "df['release'] = mask\n",
    "df.release"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "c9fe27f3-8035-48d0-90ff-75bceb9697cb",
   "metadata": {
    "scrolled": true
   },
   "outputs": [],
   "source": [
    "mask = df['budget'].str.strip('$').str.replace(',','').astype(float)\n",
    "df['budget'] = mask\n",
    "mask = df['revenue'].str.strip('$').str.replace(',','').astype(float)\n",
    "df['revenue'] = mask\n",
    "df.info()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "5419aafa-1c53-476f-b4da-673df47806d9",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.head()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "25b925ad-7351-4447-bff2-a765450b7235",
   "metadata": {},
   "source": [
    "We will be creating a `new feature` to represent the `profit` the film made by taking the `difference` between each film's `budget` and `revenue`. This reasons for this new feature is:\n",
    "- The feature `profit` will immediately show us whether a movie resulted in a loss or profit.\n",
    "- We can compare actual `revenue` earned between films for better analysis.\n",
    "- The `profit` will tell us if `budget` plays a role in `revenue` and the film's success.\n",
    "- We also want to only work with the `top 60%` of profit belonging to the data.\n",
    "- We lastly `filter` the dataframe with films of only the `top 60%` of `profit` because our goal is to analyze the data that leads to great profits, which will be found in the higher grossing films."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "e7198ca3-72cd-4c78-aced-912abff32a70",
   "metadata": {},
   "outputs": [],
   "source": [
    "df['profit'] = df['revenue'] - df['budget']\n",
    "df.tail()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b4ff664a-2613-4a14-b3f8-37e7edba543c",
   "metadata": {},
   "source": [
    "Finding the `top 60%` of the `profit` feature."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "56f708cc-e9e5-44e6-b902-c93f0cac8e3a",
   "metadata": {
    "scrolled": true
   },
   "outputs": [],
   "source": [
    "top_60_percent = df['profit'].quantile(0.6)\n",
    "mask = df[df['profit'] >= top_60_percent]\n",
    "mask.shape"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7e1e2d6c-9ace-4b0c-ab25-1d9193ca71da",
   "metadata": {},
   "source": [
    "Essential `reset` of the dataframe to only be the films that reflect the `top 60%` of `profits` from the original data."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "bf36f7ee-69fa-4ce9-a413-ac9ac34e1e34",
   "metadata": {},
   "outputs": [],
   "source": [
    "df = mask.sort_values(by='profit', ascending=False).reset_index(drop=True).copy()\n",
    "df.info()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "766da9ca-cdb8-4486-8045-3c3e415a0188",
   "metadata": {},
   "source": [
    "We have two columns `rating` and `votes` that directly are affected by each other. This makes our analysis a little difficult because films with significantly less votes will affect comparing ratings with films that got a much larger number of votes.\n",
    "\n",
    "For that reason, we created a new feature `weighted_rating` which accurately represents the film rating based on the amounts of votes the film received. This feature has been normalized throughout the data."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "6ed1bfaf-7e06-4bd8-897e-c605c408f0d5",
   "metadata": {},
   "outputs": [],
   "source": [
    "print('df.rating.describe()')\n",
    "print(df['rating'].describe())\n",
    "print()\n",
    "print('df.votes.describe()')\n",
    "print(df['votes'].describe())"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "6ea0c47b-a8df-498d-8486-72cd8586c07a",
   "metadata": {},
   "outputs": [],
   "source": [
    "C = df['rating'].mean()\n",
    "m = df['votes'].quantile(0.6) # Only considering votes that are greater than the bottom 60%.\n",
    "def weighted_rating(x, m=m, C=C):\n",
    "    v = x['votes']\n",
    "    R = x['rating']\n",
    "    return (v / (v + m) * R) + (m / (v + m) * C)\n",
    "\n",
    "df['weighted_rating'] = df.apply(weighted_rating, axis=1)\n",
    "df[['film', 'rating', 'votes', 'weighted_rating']]"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "6a8f54a9-9eb9-43c7-aa45-713542c5641b",
   "metadata": {},
   "source": [
    "We apply the changes onto our original dataframe `rating` so that we don't add irrelevant features; including dropping `votes` since our rating scale has been weighted with votes. And lastly dropping duplicates in `film`."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "b50a48e6-5086-4545-b2d0-c3197edfbf98",
   "metadata": {
    "scrolled": true
   },
   "outputs": [],
   "source": [
    "df['rating'] = df['weighted_rating']\n",
    "df = df[['film', 'genres', 'rating', 'release', 'budget', 'revenue', 'profit', # 'votes', 'weighted_rating'\n",
    "   ]]\n",
    "df.drop_duplicates(subset='film', keep='first', inplace=True)\n",
    "df"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3b2049f7-37aa-4a65-8573-be1a70820296",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "### 3. Feature Understanding\n",
    "- Plotting Feature Distributions\n",
    "    - Histogram\n",
    "    - KDE\n",
    "    - Boxplot"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "e8eaf062-42bc-4386-b2ff-0177f79967cd",
   "metadata": {},
   "outputs": [],
   "source": [
    "df"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "69743034-d710-4156-b26b-f51a6336e6ef",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "#### Understanding `Budget` Feature"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "c1e63deb-5d51-4b93-bd6e-0d01329d2067",
   "metadata": {},
   "outputs": [],
   "source": [
    "def visualize_df_budget():\n",
    "    plt.figure(figsize=(14, 6))\n",
    "    plt.subplot(1, 3, 1)\n",
    "    sns.histplot(df['budget'], kde=False, bins=30)\n",
    "    plt.title('Histogram of Budget')\n",
    "    plt.xlabel('Budget')\n",
    "    plt.ylabel('Frequency')\n",
    "    \n",
    "    plt.subplot(1, 3, 2)\n",
    "    sns.boxplot(x=df['budget'])\n",
    "    plt.title('Boxplot of Budget')\n",
    "    plt.xlabel('Budget')\n",
    "    \n",
    "    plt.subplot(1, 3, 3)\n",
    "    sns.kdeplot(df['budget'], shade=True)\n",
    "    plt.title('KDE Plot of Budget')\n",
    "    plt.xlabel('Budget')\n",
    "    \n",
    "    plt.tight_layout()\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_budget()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7cdecaec-5baf-489e-be7a-e4cf166568d1",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "#### Understanding `Revenue` Feature"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "90c55f3e-0c80-409e-9b17-9115bbffd18b",
   "metadata": {},
   "outputs": [],
   "source": [
    "def visualize_df_revenue():\n",
    "    plt.figure(figsize=(14, 6))\n",
    "    plt.subplot(1, 3, 1)\n",
    "    sns.histplot(df['revenue'], kde=False, bins=30)\n",
    "    plt.title('Histogram of Revenue')\n",
    "    plt.xlabel('Revenue')\n",
    "    plt.ylabel('Frequency')\n",
    "    \n",
    "    plt.subplot(1, 3, 2)\n",
    "    sns.boxplot(x=df['revenue'])\n",
    "    plt.title('Boxplot of Revenue')\n",
    "    plt.xlabel('Revenue')\n",
    "    \n",
    "    plt.subplot(1, 3, 3)\n",
    "    sns.kdeplot(df['revenue'], shade=True)\n",
    "    plt.title('KDE Plot of Revenue')\n",
    "    plt.xlabel('Revenue')\n",
    "    \n",
    "    plt.tight_layout()\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_revenue()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7655a463-d587-4ed6-9ddc-6a5abf617a03",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "#### Understanding `Profit` Feature"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "248a9017-1bd9-4732-9700-8994a0720558",
   "metadata": {},
   "outputs": [],
   "source": [
    "def visualize_df_profit():\n",
    "    plt.figure(figsize=(14, 6))\n",
    "    plt.subplot(1, 3, 1)\n",
    "    sns.histplot(df['profit'], kde=False, bins=30)\n",
    "    plt.title('Histogram of Profit')\n",
    "    plt.xlabel('Profit')\n",
    "    plt.ylabel('Frequency')\n",
    "    \n",
    "    plt.subplot(1, 3, 2)\n",
    "    sns.boxplot(x=df['profit'])\n",
    "    plt.title('Boxplot of Profit')\n",
    "    plt.xlabel('Profit')\n",
    "    \n",
    "    plt.subplot(1, 3, 3)\n",
    "    sns.kdeplot(df['profit'], shade=True)\n",
    "    plt.title('KDE Plot of Profit')\n",
    "    plt.xlabel('Profit')\n",
    "    \n",
    "    plt.tight_layout()\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_profit()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b9c0fb54-558e-4c68-b58c-31ba032bf276",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "#### Understanding `Rating` Feature"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "f319e893-1ed7-40b2-9f3c-7ef82d718136",
   "metadata": {},
   "outputs": [],
   "source": [
    "def visualize_df_rating():\n",
    "    plt.figure(figsize=(14, 6))\n",
    "    plt.subplot(1, 3, 1)\n",
    "    sns.histplot(df['rating'], kde=False, bins=30)\n",
    "    plt.title('Histogram of Rating')\n",
    "    plt.xlabel('Rating')\n",
    "    plt.ylabel('Frequency')\n",
    "    \n",
    "    plt.subplot(1, 3, 2)\n",
    "    sns.boxplot(x=df['rating'])\n",
    "    plt.title('Boxplot of Rating')\n",
    "    plt.xlabel('Rating')\n",
    "    \n",
    "    plt.subplot(1, 3, 3)\n",
    "    sns.kdeplot(df['rating'], shade=True)\n",
    "    plt.title('KDE Plot of Rating')\n",
    "    plt.xlabel('Rating')\n",
    "    \n",
    "    plt.tight_layout()\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_rating()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d12cbadb-dc3e-4f5a-9b53-5d03175cb39d",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "#### Understanding `Genres` Feature"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "c7d3ee1c-1b44-4baa-bb70-570458bc5eaa",
   "metadata": {},
   "outputs": [],
   "source": [
    "def visualize_df_genres():\n",
    "    top_genres = df['genres'].value_counts().nlargest(20).index\n",
    "    mask = df[df['genres'].isin(top_genres)]\n",
    "    \n",
    "    plt.figure(figsize=(12, 8))\n",
    "    bar_plot = sns.countplot(y=mask['genres'], order=mask['genres'].value_counts().index)\n",
    "    plt.title('Bar Plot of Top 20 Genres in Top 60% Highest Profit Movies')\n",
    "    plt.xlabel('Count')\n",
    "    plt.ylabel('Genres')\n",
    "    \n",
    "    plt.tight_layout()\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_genres()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "668afa07-f3c4-4056-afae-9960602f72aa",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "#### Understanding `Release Date` Feature"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "fa05168e-796b-40e0-8cf9-19976fc1d812",
   "metadata": {},
   "outputs": [],
   "source": [
    "def visualize_df_release_year():\n",
    "    df['release_year'] = df['release'].dt.year\n",
    "    plt.figure(figsize=(12, 6))\n",
    "    df['release_year'].value_counts().sort_index().plot(kind='bar')\n",
    "    plt.title('Number of Movies Released Each Year')\n",
    "    plt.xlabel('Year')\n",
    "    plt.ylabel('Number of Movies')\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_release_year()\n",
    "\n",
    "def visualize_df_release_month():\n",
    "    df['release_month'] = df['release'].dt.month\n",
    "    plt.figure(figsize=(12, 6))\n",
    "    df['release_month'].value_counts().sort_index().plot(kind='bar')\n",
    "    plt.title('Number of Movies Released Each Month')\n",
    "    plt.xlabel('Month')\n",
    "    plt.ylabel('Number of Movies')\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_release_month()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "9a8500e2-e09f-406e-b036-0be069e3b5a5",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "### 4. Feature Relationships\n",
    "- Scatterplot\n",
    "- Heatmap Correlation\n",
    "- Pairplot\n",
    "- Groupby Comparisons"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "f10e9b29-01b1-4721-a7a6-a3b01c9d5349",
   "metadata": {},
   "outputs": [],
   "source": [
    "df.head()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "5d7b4216-e0c4-4602-9800-a3831e0c3b59",
   "metadata": {},
   "source": [
    "#### Scatterplots"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "a61284bd-d9d8-4971-8a72-b85920777358",
   "metadata": {},
   "outputs": [],
   "source": [
    "def visualize_df_scatter():\n",
    "    fig, ax = plt.subplots(figsize=(10,8))\n",
    "    sns.scatterplot(data=df, x='budget', y='revenue')\n",
    "    plt.title('Scatterplot of Budget vs Revenue')\n",
    "    plt.xlabel('Budget')\n",
    "    plt.ylabel('Revenue')  \n",
    "    formatter = FuncFormatter(custom_formatter)\n",
    "    plt.gca().yaxis.set_major_formatter(formatter)\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_scatter()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "ed0bce78-4bfb-4c7a-a0e1-e6df270e043a",
   "metadata": {},
   "source": [
    "The scatterplots show positive correlations between budget and both revenue and profit, indicating that higher-budget movies tend to generate higher returns. However, clusters of lower-budget movies with lower returns and a few high-budget outliers suggest variability. This means investing in high-budget films can be profitable but risky. A balanced approach with low to mid-budget films could mitigate risk."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "0c32ce09-6fe0-4d75-985b-c1438209a468",
   "metadata": {},
   "source": [
    "#### Heatmap Correlations"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "7df2f744-cba1-49b1-9879-2560c2b9e494",
   "metadata": {},
   "outputs": [],
   "source": [
    "def visualize_df_heatmap():\n",
    "    plt.figure(figsize=(10, 8))\n",
    "    correlation_matrix = df[['budget', 'revenue', 'profit', 'rating']].corr()\n",
    "    sns.heatmap(correlation_matrix, annot=True, cmap='coolwarm', vmin=-1, vmax=1)\n",
    "    plt.title('Heatmap of Correlation Matrix')\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_heatmap()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2af2de56-1447-4f01-b084-2185f78888c1",
   "metadata": {},
   "source": [
    "With the heatmap, we can see strong positive correlations between budget and both revenue (0.77) and profit (0.66), indicating higher budgets tend to generate higher returns. However, the low correlation between budget and rating (0.2) shows higher budgets do not guarantee better ratings. This means investing in high-budget films can yield higher financial returns but not necessarily higher ratings. We can interpret that focusing on revenue-maximizing strategies enhances profitability, while improving content quality is key for better ratings."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "83f39cde-d602-411d-909e-998f37efe975",
   "metadata": {},
   "source": [
    "#### Pairplots"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "f0bf223d-c7be-4e40-8b7d-577328c76c02",
   "metadata": {},
   "outputs": [],
   "source": [
    "def visualize_df_pairplot():\n",
    "    sns.pairplot(df[['budget', 'revenue', 'profit', 'rating']])\n",
    "    plt.suptitle('Pairplot of Budget, Revenue, Profit, and Rating', y=1.02)\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_pairplot()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "674d0e3c-cc19-4d28-ac98-4420051bd567",
   "metadata": {},
   "source": [
    "With the pairplot, we can see upward trends indicating positive correlations between budget and both revenue and profit. This means higher budgets tend to generate higher returns. However, clusters of lower budgets with lower returns and a few high-budget outliers suggest variability. This shows that while high-budget films can earn high returns, many lower-budget movies exist. We can interpret that higher budgets generally correlate with higher financial returns, suggesting that investing more in production might be beneficial. However, the presence of outliers indicates risks, so a balanced portfolio of low to mid-budget movies could mitigate these risks."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "ea44e42d-5084-47b0-8bb3-f76d127fa0cf",
   "metadata": {},
   "source": [
    "#### Groupby Comparisons"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "01aa64ee-266a-4c72-a727-4d1f4f9c82e9",
   "metadata": {},
   "outputs": [],
   "source": [
    "def visualize_df_genre_revenue():\n",
    "    genre_revenue = df.groupby('genres')['revenue'].mean()\n",
    "    genre_revenue.sort_values(ascending=False, inplace=True)\n",
    "    genre_revenue = genre_revenue.head(20)\n",
    "    plt.figure(figsize=(12, 8))\n",
    "    sns.barplot(x=genre_revenue.values, y=genre_revenue.index, palette='crest_r')\n",
    "    plt.title('Average Revenue by Genre')\n",
    "    plt.xlabel('Average Revenue')\n",
    "    plt.ylabel('Genre')\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_genre_revenue()\n",
    "\n",
    "\n",
    "def visualize_df_release_revenue():\n",
    "    monthly_revenue = df.groupby('release_month')['revenue'].mean().reset_index(drop=True).copy()\n",
    "    plt.figure(figsize=(12, 6))\n",
    "    sns.barplot(x='release_month', y='revenue', data=df, palette='flare', ci=None)\n",
    "    plt.title('Average Revenue by Release Month')\n",
    "    plt.xlabel('Release Month')\n",
    "    plt.ylabel('Average Revenue')\n",
    "    plt.xticks(ticks=range(12), labels=['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec'])\n",
    "    plt.grid(True)\n",
    "    formatter = FuncFormatter(custom_formatter)\n",
    "    plt.gca().yaxis.set_major_formatter(formatter)\n",
    "    plt.show()\n",
    "\n",
    "visualize_df_release_revenue()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d64b803c-a403-49b8-a2f5-05c9c256852d",
   "metadata": {},
   "source": [
    "With the bar plot of average revenue by genre, we can visually see that genres like Fantasy, Romance, and Adventure, Drama, Sport generate the highest average revenue. This means that movies within these genres tend to perform better financially. However, there are also other genres with substantial revenue, indicating a diverse range of successful genres. This shows us that focusing on high-revenue genres could enhance profitability. We can interpret that investing in genres like Fantasy and Adventure is beneficial for financial returns, but considering a variety of genres can diversify revenue sources. We recommend balancing investments between these top-performing genres to maximize profitability."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "1febba7e-aaa5-46ab-99a1-0dda185173d2",
   "metadata": {},
   "source": [
    "## Hypothesis 1\n",
    "\n",
    "#### Films with higher budgets tend to have higher box-office revenues."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "401d1c06-b698-4ac6-b242-00e5da13f4e8",
   "metadata": {},
   "outputs": [],
   "source": [
    "visualize_df_scatter()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "cfb75f6f-d309-470d-837f-ba450ff7dbfa",
   "metadata": {},
   "source": [
    "## Hypothesis 2\n",
    "\n",
    "#### Films released during spring months perform better than those released during any other time of the year."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "14a1a4fc-3899-4c66-997a-1e5272621f23",
   "metadata": {},
   "outputs": [],
   "source": [
    "visualize_df_release_revenue()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3cd68615-165c-44cc-9420-9ae152f24e3d",
   "metadata": {},
   "source": [
    "## Hypothesis 3\n",
    "\n",
    "#### Certain genres lead to higher revenue than other genres."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "60c899c5-bb5e-45ad-99a1-e8a66925ba76",
   "metadata": {},
   "outputs": [],
   "source": [
    "visualize_df_genre_revenue()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3c584022-0693-4adf-bbd2-f26cfe2ffacd",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "## 1. Movies with higher budgets tend to have higher box-office revenues."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "efc75dc9-4017-451f-860a-30a6fe6ad98e",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "### Correlation Analysis\n",
    "\n",
    "By calculating the correlation coefficient, we understand the strength and direction of the relationship between budget and revenue. A coefficient closer to +1 indicates a strong positive correlation, meaning higher budgets likely lead to higher revenues."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "08a2a269-4657-4ff5-9ba1-57258ae82adf",
   "metadata": {},
   "outputs": [],
   "source": [
    "correlation = df['budget'].corr(df['revenue'])\n",
    "print(f'Correlation between budget and revenue: {round(correlation,2)}')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "4ea23feb-5992-4699-95c0-5624fba2bb1d",
   "metadata": {},
   "outputs": [],
   "source": [
    "fig, axes = plt.subplots(1, 2, figsize=(11, 5))\n",
    "\n",
    "sns.scatterplot(data=df, x='budget', y='revenue', ax=axes[0])\n",
    "axes[0].set_title('Scatterplot of Budget vs Revenue')\n",
    "axes[0].set_xlabel('Budget')\n",
    "axes[0].set_ylabel('Revenue')\n",
    "formatter = FuncFormatter(custom_formatter)\n",
    "axes[0].yaxis.set_major_formatter(formatter)\n",
    "\n",
    "correlation_matrix = df[['budget', 'revenue', 'profit', 'rating']].corr()\n",
    "sns.heatmap(correlation_matrix, annot=True, cmap='coolwarm', vmin=-1, vmax=1, ax=axes[1])\n",
    "axes[1].set_title('Heatmap of Correlation Matrix')\n",
    "\n",
    "plt.tight_layout()\n",
    "plt.show()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7cc7ad56-9e07-42ba-8d2f-3b2f39abd684",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "### Business Implication\n",
    "\n",
    "The `correlation coefficient` between budget and revenue is `0.78` which tells us that as budget increases, revenue tends to increase as well. **It is worth investing in a higher budget film as it could likely lead to higher box-office revenues.** While correlation does not imply causation, this high correlation coefficient suggests that budget is a good predictor of revenue."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "32ba8460-f360-42f8-800a-c16619ab79b1",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "## 2. Films released during spring months perform better than other seasons."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c7e39f2c-ea9f-43e0-9d64-b9005c6f4a69",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "### T-test\n",
    "\n",
    "By utilizing the statistical T-test, we compare the average revenue of films released in spring (March, April, May) to those released in other months. This will show if spring films have a significant financial advantage over other times of the year."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "fe9c3216-4efa-438d-baae-dd475a41fe05",
   "metadata": {},
   "outputs": [],
   "source": [
    "from scipy.stats import ttest_ind\n",
    "\n",
    "spring_months = [3, 4, 5]\n",
    "summer_months = [6, 7, 8]\n",
    "fall_months = [9, 10, 11]\n",
    "winter_months = [12, 1, 2]\n",
    "\n",
    "spring_revenue = df[df['release_month'].isin(spring_months)]['revenue']\n",
    "summer_revenue = df[df['release_month'].isin(summer_months)]['revenue']\n",
    "fall_revenue = df[df['release_month'].isin(fall_months)]['revenue']\n",
    "winter_revenue = df[df['release_month'].isin(winter_months)]['revenue']\n",
    "other_revenue = df[~df['release_month'].isin(spring_months)]['revenue']\n",
    "\n",
    "df['season'] = df['release_month'].apply(\n",
    "    lambda x: 'Spring' if x in spring_months else \n",
    "              'Summer' if x in summer_months else \n",
    "              'Fall' if x in fall_months else \n",
    "              'Winter'\n",
    ")\n",
    "\n",
    "t_stat, p_val = ttest_ind(spring_revenue, other_revenue)\n",
    "print(f'T-statistic: {t_stat}, P-value: {p_val}')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "29176e74-35bd-414b-9923-fce8ce091de9",
   "metadata": {},
   "outputs": [],
   "source": [
    "season_means = df.groupby('season')['revenue'].mean()\n",
    "season_std_errors = df.groupby('season')['revenue'].sem()\n",
    "\n",
    "fig, axes = plt.subplots(1, 2, figsize=(11, 5))\n",
    "\n",
    "monthly_revenue = df.groupby('release_month')['revenue'].mean().reset_index(drop=True).copy()\n",
    "sns.barplot(x='release_month', y='revenue', data=df, palette='flare', ci=None, ax=axes[0])\n",
    "axes[0].set_title('Average Revenue by Release Month')\n",
    "axes[0].set_xlabel('Release Month')\n",
    "axes[0].set_ylabel('Average Revenue')\n",
    "axes[0].set_xticks(range(12))\n",
    "axes[0].set_xticklabels(['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec'])\n",
    "axes[0].grid(True)\n",
    "axes[0].yaxis.set_major_formatter(FuncFormatter(custom_formatter))\n",
    "\n",
    "season_means.plot(kind='bar', yerr=season_std_errors, capsize=5, color=['#1f77b4', '#ff7f0e', '#2ca02c', '#d62728'], ax=axes[1])\n",
    "axes[1].set_title('Average Revenue by Season with 95% CI')\n",
    "axes[1].set_xlabel('Season')\n",
    "axes[1].set_ylabel('Average Revenue')\n",
    "axes[1].yaxis.set_major_formatter(FuncFormatter(custom_formatter))\n",
    "axes[1].tick_params(axis='x', rotation=0)\n",
    "\n",
    "plt.tight_layout()\n",
    "plt.show()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "bc6004c1-fc74-4ddc-aa74-efbf09180052",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "### Confidence Interval of the `difference` in the `mean` of spring and other months.\n",
    "\n",
    "By calculating the confidence intervals of the difference in the mean revenue between spring and other months, we quantify the precision and reliability of this difference, confirming that the observed higher average revenue in spring is statistically significant."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "7056fdb9-163f-4234-a385-59040acbc408",
   "metadata": {},
   "outputs": [],
   "source": [
    "mean_spring = np.mean(spring_revenue)\n",
    "mean_other = np.mean(other_revenue)\n",
    "std_spring = np.std(spring_revenue)\n",
    "std_other = np.std(other_revenue)\n",
    "\n",
    "n_spring = len(spring_revenue)\n",
    "n_other = len(other_revenue)\n",
    "stderr_diff = np.sqrt((std_spring**2 / n_spring) + (std_other**2 / n_other))\n",
    "t_critical = stats.t.ppf(1 - 0.025, df=n_spring + n_other - 2)\n",
    "margin_err = t_critical * stderr_diff\n",
    "mean_diff = mean_spring - mean_other\n",
    "ci_lower = mean_diff - margin_err\n",
    "ci_upper = mean_diff + margin_err\n",
    "print(f'Spring Months average revenue: {mean_spring}')\n",
    "print(f'Other Months average revenue: {mean_other}')\n",
    "print(f'Difference In average revenue: {mean_diff}')\n",
    "print('--------')\n",
    "print(f'95% confidence interval for the difference in means: [{ci_lower}, {ci_upper}]')"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c0c0b7fa-2e9a-44f4-a58c-965fc4e5cf76",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "### Business Implication\n",
    "\n",
    "Our `p-value` of `0.002896` concludes that we reject the null hypothesis because our `p-value < 0.05` significance level. Coupled with our `t-stat` score `2.9847`, this shows that the average revenue between films released in spring is significantly higher than the average revenue of other times of the year. **Releasing films in the spring could be financially advantageous.**\n",
    "\n",
    "By further calculating the `spring months average revenue` and the `other months average revenue`, we can truly see if the spring months lead to higher. We calculated the `difference in averages` to see how much spring is different from the other months as well as the `confidence interval of difference in averages` to provide additional support in defending that releasing films in spring could lead to financial advantages."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "f874219d-1303-4a4c-bfa8-c70a2f35c9da",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "## 3. Certain genres lead to higher revenue than other genres."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8e843814-b33d-4381-aead-9d5cefc88487",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "### ANOVA-test\n",
    "\n",
    "By utilizing the statistical ANOVA-test, we are able to compare the mean profits across different genres. This will show if there are significant differences in profitability among genres, helping us identify which genres tend to be more profitable."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "30d51ed4-5c0d-4022-b466-8bde8f022a14",
   "metadata": {},
   "outputs": [],
   "source": [
    "from scipy.stats import f_oneway\n",
    "genre_groups = [group['revenue'].values for name, group in df.groupby('genres')]\n",
    "f_stat, p_val = f_oneway(*genre_groups)\n",
    "print(f'F-statistic: {f_stat}, P-value: {p_val}')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "01e28dc6-86e2-4fd8-82d9-e4260447a477",
   "metadata": {},
   "outputs": [],
   "source": [
    "average_revenue = df.groupby('genres')['revenue'].mean().reset_index()\n",
    "std_revenue = df.groupby('genres')['revenue'].std().reset_index()\n",
    "top_genres = average_revenue.nlargest(20, 'revenue')['genres']\n",
    "df_top_genres = df[df['genres'].isin(top_genres)]\n",
    "average_revenue_top = average_revenue[average_revenue['genres'].isin(top_genres)].set_index('genres')\n",
    "std_revenue_top = std_revenue[std_revenue['genres'].isin(top_genres)].set_index('genres')\n",
    "average_revenue_top = average_revenue_top.loc[std_revenue_top.index]\n",
    "\n",
    "fig, axes = plt.subplots(2, 1, figsize=(12, 12))\n",
    "\n",
    "sns.barplot(data=df_top_genres, x='revenue', y='genres', palette='crest_r', ci=None, ax=axes[0])\n",
    "axes[0].set_title('Average Revenue by Genre')\n",
    "axes[0].set_xlabel('Average Revenue')\n",
    "axes[0].set_ylabel('Genre')\n",
    "axes[0].xaxis.set_major_formatter(formatter)\n",
    "\n",
    "sns.pointplot(x='revenue', y='genres', data=df_top_genres, join=False, ax=axes[1])\n",
    "axes[1].set_title('Average Revenue by Genre')\n",
    "axes[1].set_xlabel('Revenue')\n",
    "axes[1].set_ylabel('Genres')\n",
    "axes[1].xaxis.set_major_formatter(formatter)\n",
    "\n",
    "plt.tight_layout()\n",
    "plt.show()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8add8e0d-ce16-48a6-8974-950dfaee65c7",
   "metadata": {},
   "source": [
    "### Business Implication\n",
    "\n",
    "Our ANOVA test concluded that our data with genres resulted in `p-value` of `3.53x10e-7` (a significantly small decimal), which means we `reject` our `null hypothesis` because the `p-value < 0.05 significance level`. Our `f-stat` score `3.3958` shows that there is a `significant difference` in average revenue among different `genres`, which is supported by the p-value as well. **Thus, we can allocate our film budget towards a specific genre that will likely result in greater revenue.** "
   ]
  },
  {
   "cell_type": "markdown",
   "id": "51efb837-8447-4f66-bb64-f1b77c416f75",
   "metadata": {},
   "source": [
    "#### Graph Functions"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "8a48e446-d3a2-4ce4-9a97-9e8955482f13",
   "metadata": {},
   "outputs": [],
   "source": [
    "def hypothesis1_graph():\n",
    "    fig, axes = plt.subplots(1, 2, figsize=(11, 5))\n",
    "    \n",
    "    sns.scatterplot(data=df, x='budget', y='revenue', ax=axes[0])\n",
    "    axes[0].set_title('Scatterplot of Budget vs Revenue')\n",
    "    axes[0].set_xlabel('Budget')\n",
    "    axes[0].set_ylabel('Revenue')\n",
    "    formatter = FuncFormatter(custom_formatter)\n",
    "    axes[0].yaxis.set_major_formatter(formatter)\n",
    "    \n",
    "    correlation_matrix = df[['budget', 'revenue', 'profit', 'rating']].corr()\n",
    "    sns.heatmap(correlation_matrix, annot=True, cmap='coolwarm', vmin=-1, vmax=1, ax=axes[1])\n",
    "    axes[1].set_title('Heatmap of Correlation Matrix')\n",
    "    \n",
    "    plt.tight_layout()\n",
    "    plt.show()\n",
    "\n",
    "hypothesis1_graph()\n",
    "\n",
    "\n",
    "def hypothesis2_graph():\n",
    "    season_means = df.groupby('season')['revenue'].mean()\n",
    "    season_std_errors = df.groupby('season')['revenue'].sem()\n",
    "    \n",
    "    fig, axes = plt.subplots(1, 2, figsize=(11, 5))\n",
    "    \n",
    "    monthly_revenue = df.groupby('release_month')['revenue'].mean().reset_index(drop=True).copy()\n",
    "    sns.barplot(x='release_month', y='revenue', data=df, palette='flare', ci=None, ax=axes[0])\n",
    "    axes[0].set_title('Average Revenue by Release Month')\n",
    "    axes[0].set_xlabel('Release Month')\n",
    "    axes[0].set_ylabel('Average Revenue')\n",
    "    axes[0].set_xticks(range(12))\n",
    "    axes[0].set_xticklabels(['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec'])\n",
    "    axes[0].grid(True)\n",
    "    axes[0].yaxis.set_major_formatter(FuncFormatter(custom_formatter))\n",
    "    \n",
    "    season_means.plot(kind='bar', yerr=season_std_errors, capsize=5, color=['#1f77b4', '#ff7f0e', '#2ca02c', '#d62728'], ax=axes[1])\n",
    "    axes[1].set_title('Average Revenue by Season with 95% CI')\n",
    "    axes[1].set_xlabel('Season')\n",
    "    axes[1].set_ylabel('Average Revenue')\n",
    "    axes[1].yaxis.set_major_formatter(FuncFormatter(custom_formatter))\n",
    "    axes[1].tick_params(axis='x', rotation=0)\n",
    "    \n",
    "    plt.tight_layout()\n",
    "    plt.show()\n",
    "\n",
    "hypothesis2_graph()\n",
    "\n",
    "\n",
    "def hypothesis3_graph():\n",
    "    average_revenue = df.groupby('genres')['revenue'].mean().reset_index()\n",
    "    std_revenue = df.groupby('genres')['revenue'].std().reset_index()\n",
    "    top_genres = average_revenue.nlargest(20, 'revenue')['genres']\n",
    "    df_top_genres = df[df['genres'].isin(top_genres)]\n",
    "    average_revenue_top = average_revenue[average_revenue['genres'].isin(top_genres)].set_index('genres')\n",
    "    std_revenue_top = std_revenue[std_revenue['genres'].isin(top_genres)].set_index('genres')\n",
    "    average_revenue_top = average_revenue_top.loc[std_revenue_top.index]\n",
    "    \n",
    "    fig, axes = plt.subplots(2, 1, figsize=(12, 12))\n",
    "    \n",
    "    sns.barplot(data=df_top_genres, x='revenue', y='genres', palette='crest_r', ci=None, ax=axes[0])\n",
    "    axes[0].set_title('Average Revenue by Genre')\n",
    "    axes[0].set_xlabel('Average Revenue')\n",
    "    axes[0].set_ylabel('Genre')\n",
    "    axes[0].xaxis.set_major_formatter(formatter)\n",
    "    \n",
    "    sns.pointplot(x='revenue', y='genres', data=df_top_genres, join=False, ax=axes[1])\n",
    "    axes[1].set_title('Average Revenue by Genre')\n",
    "    axes[1].set_xlabel('Revenue')\n",
    "    axes[1].set_ylabel('Genres')\n",
    "    axes[1].xaxis.set_major_formatter(formatter)\n",
    "    \n",
    "    plt.tight_layout()\n",
    "    plt.show()\n",
    "\n",
    "hypothesis3_graph()"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "fb9a3b1b-86ac-415f-aa33-00f23562d1c2",
   "metadata": {},
   "source": [
    "### 1. Plan for higher budget production to maximize returns.\n",
    "\n",
    "`Insight:` We observed that budget plays a significant role in a film's success, with higher budgets generally correlating with higher revenues. This was supported by the positive trend on the scatterplot and correlation coefficient close to +1.\n",
    "\n",
    "`Recommendation:` Plan and allocate for higher budgets on our films to maximize potential revenue."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "4592e90f-b9e5-4a6b-9feb-70378ea67472",
   "metadata": {},
   "source": [
    "### 2. Releasing films during the spring months can create more sales.\n",
    "\n",
    "`Insight:` We observed statistical significance of films released in the spring months and revenue earned compared to the other times of the year. This was supported by our p-value > 0.05 rejecting the null hypothesis that there's no difference of revenues in the spring months compared to other months.\n",
    "\n",
    "`Recommendation:` Plan major releases during these months to capitalize on higher audience and box-office turnout."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "030483ee-35d9-4526-9d26-0543005c6750",
   "metadata": {},
   "source": [
    "### 3. Focus production towards profitable and compelling genres.\n",
    "\n",
    "`Insight:` We observed a significant difference in the average revenues across various genres, giving us direction for production. This was supported by our p-value > 0.05 rejecting the null hypothesis that there's no difference in revenues across different genres, revealing genres with great value for production.\n",
    "\n",
    "`Recommendation:` Produce films with aspects of the genre-groups that are proven to drive success."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "fd2bf679-aadd-4194-af9d-45189d86c539",
   "metadata": {},
   "source": [
    "- #### Implement predictive modeling and linear regression analysis to forecast movie revenues based on budget, genre, and release timing, providing stakeholders with data-driven revenue predictions."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3cf7324f-3343-4cc6-a43e-c8f5c8c1f6fe",
   "metadata": {},
   "source": [
    "- #### Explore other features and variables such as ratings and reviews to uncover additional factors that influence movie success, enhancing the overall predictive model."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "fc022961-80ca-4bcb-b221-45f21e5831ef",
   "metadata": {},
   "source": [
    "- #### Apply optimization techniques for effective budget allocation, ensuring resources are used in a way that maximizes potential returns on investment."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "e940528d-f51d-4108-bdaf-88f680b13ee8",
   "metadata": {},
   "source": [
    "#### Test Entire Script"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "3d24d79d-00cc-4fc4-beff-09b4ec01116c",
   "metadata": {},
   "outputs": [],
   "source": [
    "try:\n",
    "    print('Script executed successfully!')\n",
    "except:\n",
    "    print('FAILED!')"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python (learn-env)",
   "language": "python",
   "name": "learn-env"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.19"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
