# DS440-project
This is a project for DS 440. The original model of Wine predic comes from red_wine_quality_prediction.
We are very grateful to them for making their model and data public for others to use. The following is the citation required by the original author:   



    
"
Niyogisubizo, J., Ninteretse, J. de D. ., Nziyumva, E., Nshimiyimana, M. ., Murwanashyaka, E. ., & Habiyakare, E. (2024). Towards Predicting the Quality of Red Wine Using Novel Machine Learning Methods for Classification, Data Visualization and Analysis. Artificial Intelligence and Applications. https://doi.org/10.47852/bonviewAIA42021999

Created by: : Jovial Niyogisubizo

jovialniyo93@gmail.com
  
Github Link: https://github.com/jovialniyo93/red_wine_quality_prediction
"

    
  
We designed the front-end and back-end based on this model. This project includes the front-end and back-end developed based on JavaScript. Please make sure that you have JavaScript-related components in your environment before use.





Please follow the steps below to start  
1. Unzip the file Wine predict; the file is a bit large; please be patient.
2. Check your Python version; if it is higher than 3.20, you need to set up Virtual Environments in Python 3.11. or lower.
3. Install js.node componts. Check if you have a C++ compiler installed. If not, install one.
4. Activate the backend  
  cd .\backend\
    pip install -r requirements.txt  
    python app.py

5. Activate the frontend  
  cd .\frontend  
  npm install web-vitals  
  npm install @mui/material @emotion/react @emotion/styled  
  npm start  
   
    
    
    
       
If doesn't work, try to roll back the numpy using pip install numpy==1.26.4
We recommend running the program in a Windows environment, and if you follow the instructions, it should work fine in Windows. We tried running it in a Mac, and there were probably issues that we couldn't resolve.
