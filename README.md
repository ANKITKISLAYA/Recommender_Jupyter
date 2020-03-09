# Recommender_Jupyter

In this repositary all the files are the steps which led to the development of recommender system 

ANKITKISLAYA/Recommender-System   is the repositary which contains the final deployment code of recommender system in IIS server

1.RecSys.ipynb  --  is where i tried to fit and train the already cleaned and munged data in surprise library and generated the recommendations

3.RecSys_InsertMongo.ipynb  --   is where i am reading real data from mongodb and performed data cleaning and munging and generated cosine 
  similarity matrix using surprise library . Also inserted this cosine similarity matrix to mongodb .
  
2.RecSys_2ndPart_GeneratingRecommendations.ipynb    --  in this file i am generating top n recommendations using cosine similarity matrix
stored in mongodb in previous step and also filtering recommendations based on warehouseid


4.RecSys_Organised _Class.ipynb   --  in this file i organised all the steps from reading , cleaning , munging , training , generating ,
inserting back the similarity matrix under classes and methods .

5.RecSys_ReadingPickeledData.ipynb  --    this is another method in which i stored the cosine similarity matrix dataframe using pickle
  and generated the recommendations
  
6.RecSys_ReadingPickeld_HDF5.ipynb  --  in this i used pickeled dataframe as well as stored dataframe in HDF5 storage format.

7.RecSys_inserting_InsertingItemsAlongWarehouseid.ipynb  --- In this file i read transactions around all warehouses and grouped all the 
items w.r.t to warehouseid and inserted it into mongodb

8.RecSys using sklearn.ipynb  --  In this file i am using sklearn cosine similarity module to generate cosine similarity matrix

Rest are the example  datasets used in creating recommender systems











