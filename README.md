# snowpeopleApp
  
 This is the repo for an interactive deep learning image classifier. It suppports detection of 2 categories of snowmen: abominable, and Olaf. 
  
  Source data: The model is trained on 2 classes, so it works best when applied to differentiating between the abominable snowman and the friendly snowman 'Olaf' from Disney's 'Frozen'. It does work on permutations of classic features, recognizing Olaf when his features appear on a toilet paper roll for example, but won't likely generalize beyond these 2 very specific classes of snowman that it was trained on. 
  
  This repo contains code for the model, and a simple front-end hosted on mybinder.org where you can upload your own image and see classification results. Details on the files, and data used for training below. 
  
 * export-81MB.pkl - Original sized model. 
  Built with resnet18, and 300 images from Bing search API: 150 images of abominable snowman, 150 of Olaf. 
  
 * requirements.txt - requirements file lists dependencies. 
  
 * snowpeople_voila.ipynb - Notebook with basic python widgets for UI, and path to model file that Binder uses to generate the production UI. 
  
  
  
  
  
