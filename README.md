# FlowBeat: Music Recommendation Web Application

## Overview
FlowBeat is a music recommendation web application built using Flask as the backend framework. Users can select their preferred music genre from a visually appealing dropdown interface, and the app generates song recommendations based on the selected genre. The interface is styled for a modern music platform experience, similar to services like Spotify. The recommendations also include suggestions for similar genres that users may enjoy, based on a graph-based affinity model.

## Features
- *Genre Selection*: Users can choose from a wide variety of music genres using a custom dropdown interface.
- *Music Recommendations*: Provides personalized song recommendations for the selected genre.
- *Similar Genre Suggestions*: Suggests genres related to the user's chosen genre, enhancing the music discovery experience.
- *Modern UI Design*: Styled using CSS to offer a sleek, dark-themed design with interactive elements.

## Technologies Used
- *Flask*: The backend is built with Flask, serving the HTML, CSS, and handling form submissions.
- *HTML, CSS, JavaScript*: The front-end components include custom styling and interactive dropdown elements.
- *NetworkX*: The graph visualization and affinity recommendations are powered by NetworkX, a Python library for graph creation and manipulation.

## Graph Application
This project utilizes a graph-based model to establish connections between different music genres, enabling an advanced recommendation system. The graph is structured as follows:
- *Nodes*: Each node represents a musical genre (e.g., Rock, Pop, Jazz).
- *Edges*: There are directed edges connecting each genre to a central "Recommendations" node. From this central node, other edges branch out to nodes representing similar genres, providing related suggestions.
- *NetworkX Usage*: The graph is generated using the NetworkX library to
