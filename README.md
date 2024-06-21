# Fault_Detection
Fault Detection in Pneumatic Systems

TimeGAN class definition:

TimeGAN class is defined to encapsulate the functionality of a TimeGAN model.
__init__ method: Initializes the TimeGAN model with parameters like sequence length (seq_len), dimension (dim), hidden dimensions (hidden_dim), number of layers (num_layers), and other parameters (gamma, beta).
build_generator method: Defines a generator model using tf.keras.Sequential API. It consists of an LSTM layer followed by dropout and a fully connected layer (TimeDistributed ensures dense layer is applied to each time step independently).
build_discriminator method: Defines a discriminator model using tf.keras.Sequential API. It includes an LSTM layer followed by dropout and a dense layer with sigmoid activation for binary classification.
train method: Prepares the models for training by compiling them with appropriate loss functions and optimizers. The actual training loop is currently a placeholder (pass statement).
generate method: Generates synthetic data by feeding random data into the generator model.


Reads CSV files (training_set _labelled.csv, validation_set _labelled.csv, testing_set _labelled.csv) containing data.
Cleans each dataset using clean_data function to ensure numeric compatibility.
Scales the cleaned training and validation data using MinMaxScaler.
Initializes a TimeGAN model (timegan_model) with specified parameters.
Trains the TimeGAN model on the scaled training data (train_data_scaled) for 100 epochs with a batch size of 64.
Generates synthetic data (synthetic_data) using the trained TimeGAN model.
Handles NaN values in synthetic data and reshapes it for compatibility.
Inversely transforms the scaled synthetic data (synthetic_data_scaled) back to its original scale.
Saves the synthetic data to a CSV file (synthetic_data_timegan.csv) and prints shapes of original and synthetic data for verification.
