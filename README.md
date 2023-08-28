# Speech-Based Contact Search List using Linear Predictive Coding and Hidden Markov Model

The Speech-Based Contact Search List is an innovative application that enables users to search for contact details using voice commands. This project leverages the power of Linear Predictive Coding (LPC) and Hidden Markov Model (HMM) probabilistic models to facilitate accurate voice-based contact searches. The application is implemented in C++ and built using Microsoft Visual Studio 2015.

## Features

- **Voice-Based Contact Search:** Users can perform contact searches by speaking the name or other relevant information of the desired contact.

- **Dynamic Training:** The application is designed to dynamically train itself during runtime. This means that as new contacts are added or existing ones are updated, the underlying models can adapt and improve search accuracy.

## Project Structure

### Group9_SearchContactList.vcxproj

This file serves as the main project file for the VC++ project generated using the Application Wizard. It contains information about the Visual C++ version used to generate the file, as well as details about the selected platforms, configurations, and project features.

### Group9_SearchContactList.vcxproj.filters

This filters file corresponds to the project's file structure. It establishes associations between the files in the project and specific filters, facilitating organized grouping of files within the Visual Studio IDE.

### Group9_SearchContactList.cpp

This is the primary source file of the application. It contains the code responsible for displaying the application's user interface and handling its functionalities, including capturing voice input and triggering contact searches.

### Form1.h

This header file contains the implementation of the main form class and the `InitializeComponent()` function, which defines the visual layout and components of the application's user interface.

### AssemblyInfo.cpp

This file contains custom attributes that can modify assembly metadata, providing information about the application such as version details.

### StdAfx.h, StdAfx.cpp

These files are used for building a precompiled header (PCH) file named `Group9_SearchContactList.pch` and a precompiled types file named `StdAfx.obj`.

## Usage

1. Launch the application using Microsoft Visual Studio 2015.
2. The application's main form will be displayed, allowing voice-based contact searches.
3. Utter the name or relevant details of the contact you wish to find.
4. The application will process your voice input using Linear Predictive Coding and Hidden Markov Model probabilistic models to search and display the contact details.

## Contributing

This project is intended for learning purposes and can be further enhanced with additional features, improvements, and bug fixes. Contributions are welcome; feel free to fork the repository and create pull requests.


/////////////////////////////////////////////////////////////////////////////
