# Signature Verification Project

This project implements a model for detecting fraud or genuine signatures, using Python for development and Streamlit for deployment.

## Features

- **Model Training**: Utilizes machine learning techniques to train on signature data.
- **Real-time Verification**: Deploys the model using Streamlit for web-based signature verification.
- **User-friendly Interface**: Provides an intuitive interface for verifying registered signatures.

## Technologies Used

- **Python**: Core programming language.
- **Streamlit**: Framework for deploying the web application.
- **Machine Learning Libraries**: Scikit-learn, TensorFlow, numpy, os.

## Further details

- 'Real' and 'forged' folders contain dataset denoting real and forged samples respectively.
- 'Features' and 'TestFeatures' folder will be created once the code is executed, subsequently saving the trained images.

## Important Note

- Images are stored in the format : XXXZZZ_YYY
- XXX denotes id of the person who has signed on the document(ex -001)
- ZZZ denotes the id of the person to whom the sign belongs in actual(ex- 001)
- YYY denotes the n'th no. of attempt
- Now if XXX == ZZZ then image is genuine otherwise the signature is forged
