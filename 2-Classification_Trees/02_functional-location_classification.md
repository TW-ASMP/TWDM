## Top-Level functional-location Classification

The following is a sample of the Toronto Water's functional-location classification.  

* Discrete Asset functional-location*
    * generator functional-location
        * backup generator functional-location
        * emergency generator functional-location
    * breaker functional-location
        * bus feeder breaker functional-location
        * line protection breaker functional-location
        * load breaker functional-location
        * tie-breaker functional-location
* Collection of Assets functional-location*
    * functional structure functional-location
        * system block
        * facility
            * pumping station
            * water treatment facility
            * wastewater treatment facility
            * lab
            * yard
        * process
        * Linear Functional Structure functional-location*
            * system train functional-location 
            * line functional-location
                * simple line functional-location
                * primary path line functional-location
            * junction functional-location
    * Defined Set of functional-locations*
        * defined set of discrete assets
        * defined set of functional structures


## Requirements for Implementer

* []REQ Nyh7RPjEgl #IMP "classes names specified in title-case and with an asterisk symbol shall have the appliable to individual property, found in the class object, set to false"

## Notes

* []TODO #TW: the following should be moved to the asset classification. 
    * system on a skid 
    * system of standardized modular parts