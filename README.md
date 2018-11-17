# Welcome to Flowriter

### The API endpoints are at:</h3>
+ [/ross](https://flowriter.studio/ross)
+ [/plot/\<plot_point\>](https://flowriter.studio/climax)
    + Plot points are:
        + inciting-event
        + first-plot-point
        + first-pinch-point
        + midpoint
        + second-pinch-point
        + third-plot-point
        + climax
        + climactic-moment
        + resolution
        + notes
+ [/lyric/beyonce](https://flowriter.studio/lyric/beyonce)
    + You can use any artist available on Spotify.
    + If the model for that artist is not on the server, it will take a few minutes to generate a model.
+ [/prompt](https://flowriter.studio/prompt)
+ [/kant/available](https://flowriter.studio/kant/available)
    + Available titles are:
        + critique of pure reason
        + critique of practical reason
+ [/kant/short_sentence/\<string:title\>](https://flowriter.studio/kant/short_sentence/critique%20of%20pure%20reason)
+ [/kant/sentence/\<string:title\>](https://flowriter.studio/kant/sentence/critique%20of%20pure%20reason)

### Run locally
Open a terminal and run the following commands:

    # Create a virtual environment
    python3 -m venv venv

    # Activate the virtual environemnt
    . venv/bin/activate

    # Install required libraries
    pip install -r requirements.txt

    # Start the development server
    python3 app.py

### Deploying to server
This API can be automatically deployed to a server using this Ansible code:
https://github.com/kantsdog/flowriter_studio_deploy