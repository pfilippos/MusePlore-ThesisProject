# MusePlore-ThesisProject
Thesis Application

-! Not yet uploaded due to copyright reasons !-

A 3d interactive museum application.
The app was created using Unity.
The app stores all the locomotion and eye tracking data during each exploration named after the unique id of the player given by the Session Id system implemented in the app.

Eye tracker :
The eye tracker that is supported is the Fusion Pro by tobii which is intended for research use.
These data are stored via the Tobii Unity sdk in an XML format.
No previous implementation for processing was found so python scripts were created from scratch in order to preprocess them and extract the fixation points.
