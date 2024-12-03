# Steps to Download Images from URLs in a Spreadsheet using Google Colab

### Step 0: Open Google Colab
1. Go to [Google Colab](https://colab.research.google.com/) in your web browser.
2. Click "New Notebook" to create a blank Python notebook.

### Step 1: Prepare Your Spreadsheet

#### 1. Create a Spreadsheet
- Use **Excel** or **Google Sheets** to create a column of image URLs.
- Example:

    | Image_URL                      |
    |--------------------------------|
    | https://example.com/image1.jpg |
    | https://example.com/image2.png |

#### 2. Save the file as CSV (Comma-Separated Values)
- **In Excel**: 
    - File → Save As → Choose "CSV (Comma delimited) (*.csv)".
- **In Google Sheets**: 
    - File → Download → Comma Separated Values (.csv).

#### 3. Upload the CSV file to Colab
- Click the **folder icon** on the left-hand side of Colab.
- Click the **upload icon** (looks like an upward arrow).
- Select your `.csv` file and upload it.

### Step 2: Write the Code in Colab
Copy and paste the following code into a cell in your Colab notebook:
