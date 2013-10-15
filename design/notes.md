#Generate

* Site
    - List of users
        - Attributes 
            - Name
            - Email (private)
        - Trail
            - Lazy list of streams (last element is latest version)
        - List of streams
            - Stream :: Input -> Time -> [Doubles]
                - Attributes
                    - Channels :: Int
                    - Name :: String
        - List of sources
            - SoundCloud URL
            - [Live][audioinput]
                - Name
                - Description

* Primitives (sketch)

    Everything is a stream.  
    A stream is either primitive or compound.  
    An expression defines a stream.  

* Questions
    - Is time absolute or relative?
    - Look back in time? (for non-interactive streams, i.e streams with no input)

[audioinput]: http://updates.html5rocks.com/2012/09/Live-Web-Audio-Input-Enabled
    
