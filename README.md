# Medical Chatbot Project

This project focused on developing an intelligent medical chatbot designed to assist doctors by summarizing patient complaints and medical histories. The motivation behind the project is to address the challenge of handling large volumes of patient data efficiently, reducing the time doctors spend manually reviewing patient notes, and improving the overall patient experience.

We implemented a Natural Language Processing pipeline using the T5 model to generate concise summaries of patient problems based on raw input text. The project involved fine-tuning the T5 transformer model on a medical dataset consisting of patient descriptions, complaints, and diagnostic notes. We worked with 250,000 patient descriptions so that the model could understand what patients want when they are sick. The chatbot takes in a patient's problem description, processes it, and returns a summary. Based on that summary, the model calls an API through Streamlit apps to help the patient understand what needs to be done.

This project not only gives patients suggestions but also stores their past information. In our body, one problem is often related to other problems. So, based on the patient's previous issues, the chatbot provides feedback. It not only helps the patient but also assists doctors by informing them of the patient's previous conditions. This comprehensive approach enhances the quality of care and enables more informed decision-making.

### Links

- **Google Drive Link**: [Download Dataset](https://drive.google.com/drive/folders/1v6KRSdGiOeqN2Slg9CyqTZWFc07XPNR2?usp=share_link)
- **GitHub API**: [GitHub Repo](https://github.com/Md-SadmanSakib/nlp_project.git)
- **Render API Link**: [Render API](https://nlp-project-kpf8.onrender.com)


--------
## Setup Instructions

To run the code properly, you need to install the required dependencies from the `requirements.txt` file by using the following command:

```bash
pip install -r requirements.txt
```


After installing the dependencies, navigate to the notebooks folder and download the .ipynb file.

For the dataset, you can download it from the following Google Drive link:
https://drive.google.com/drive/folders/1v6KRSdGiOeqN2Slg9CyqTZWFc07XPNR2?usp=share_link



