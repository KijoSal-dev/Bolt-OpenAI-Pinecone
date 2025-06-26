# Bolt-OpenAI-Pinecone
# Code Search Slack Bot

This project implements a Slack bot that allows users to search for code snippets using a `/codesearch` slash command. The bot utilizes OpenAI for generating embeddings of the code snippets and user queries, and Pinecone for indexing and searching the embeddings.

## Features

*   Search code snippets directly from Slack using the `/codesearch` command.
*   Returns the top 3 most relevant code snippets based on the search query.

## Prerequisites

*   Python 3.6 or higher
*   Slack API Token and Signing Secret
*   OpenAI API Key
*   Pinecone API Key and Environment
*   A Pinecone index named "code-snippets"

## Setup

1.  **Install Dependencies:**

    Run the following command to install the required Python packages:
