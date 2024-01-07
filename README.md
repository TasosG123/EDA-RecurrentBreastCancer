# EDA-RecurrentBreastCancer

Dataset Description:

The Recurrent_BreastCancerDataset, sourced from the Oncology Institute, is a valuable resource for researchers and practitioners in the field of oncology. With its roots in machine learning literature, this dataset has been a recurring presence and offers insights into the recurrence patterns of breast cancer.

Dataset Overview:

Instances: 286
Classes: no-recurrence-events, recurrence-events

Attributes Description:
- age: Patient's age categorized into ranges (e.g., 10-19, 20-29, etc.).
- menopause: Menopausal status, characterized as lt40 (less than 40), ge40 (greater equal to 40), or premeno.
- tumor-size: Size of the tumor, categorized into specific ranges (in mm).
- inv-nodes: The number (range 0 - 39) of axillary lymph nodes that contain metastatic breast cancer visible on histological examination: 0-2, 3-5, 6-8, 9-11, 12-14, 15-17, 18-20, 21-23, 24-26, 27-29, 30-32, 33-35, 36-39.
- node-caps: If cancer does metastasize to a lymph node, although outside the tumor's original site, it may remain "contained" by the capsule of the lymph node. However, over time, and with more aggressive disease, the tumor may replace the lymph node and then penetrate the capsule, allowing it to invade the surrounding tissues: yes, no.
- deg-malig: The histological grade (range 1-3) of the tumor. Tumors that are grade 1 predominantly consist of cells that, while neoplastic, retain many of their typical characteristics. Grade 3 tumors predominately comprised of highly abnormal cells: 1, 2, 3.
- breast: The affected breast, identified as left or right.
- breast-quad: Quadrant of the breast affected (e.g., left-up, right-low).
- irradiat: Whether the patient underwent irradiation (yes or no).
- target: no-recurrence-events: Instances indicating no recurrence of breast cancer, recurrence-events: Instances indicating a recurrence of breast cancer.

Tools used: Pandas , MatPlotLib , Seaborn , Plotly libraries.

This EDA was performed for practice purposes.
