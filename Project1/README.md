# Data extraction, processing (ETL) and visualization

## Project description
This is a data extraction project from a public website (city of Boston, USA), where data is extracted and saved locally. After that, the data is saved in S3 in medallion format (bronze, silver and gold) processed by the Glue tool, which integrates with S3, between treatments, table view in Athena and viewed in QuickSight.

`The cloud used throughout the process is AMAZON - AWS`

<br/>
 <br/>
 <div style="text-align: center;">
  <picture>
    <img width="1000px" src="https://github.com/julianasantimaria/Projects_AWS/blob/HTML/Project1/Data%20Extraction%2C%20project%2C%20treatment%20and%20Implementation.png">
  </picture>
</div>

 <br/>

## Project Features
- **HTTP Requests**: Performs GET operations.
- **Extension handling**: Extracts and transforms data in JSON format, for CSV and Parquet.
- **Interacts with Multiple Endpoints**: Accesses different API endpoints from the city of Boston, USA.
- **Authentication and Pagination**: Manages authentication and results pagination in AWS.

## requirements
- Python 3.8 or higher
- AWS account


## Installation
1. **Navigate to the project directory**:
    ```bash
    git clone [URL the your repository]
    ```
2. **Navigate to the project directory**:
    ```bash
    cd API_Github_PROJECTAWS
    ```
3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Configuration
- **Environment Variables**: Copy the file `.env.example` for `.env` and fill in the necessary variables (example: `GITHUB_TOKEN=your_token_here`).

- **Visualization in Jupyter Notebook**:
    Open the `extraction.ipynb` for the vision all extraction data for s3 AWS.

## Contributions
To contribute to the project, follow these steps:
1. **Fork** the repository.
2. **Criete your Feature Branch** (`git checkout -b feature/AmazingFeature`).
3. **Commit yours Changes** (`git commit -m 'Add some AmazingFeature'`).
4. **Push to the Branch** (`git push origin feature/AmazingFeature`).
5. **Open a Pull Request**.

## Contact
- **Nome:** Juliana Santimaria
- **E-mail:** juliana.santimaria2@gmail.com



