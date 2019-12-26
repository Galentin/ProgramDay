# ProgramDay

Build and Run

    gradle bootRun  
    
Example

    request: http://localhost:8080/?year=2019
    response: {"errorCode":200,"dataMessage":"13/09/19"}
 
    request: http://localhost:8080/?year=1996
    response: {"errorCode":200,"dataMessage":"12/09/96"}
    
    request: http://localhost:8080/?year=2025
    response: {"errorCode":200,"dataMessage":"13/09/25"}
