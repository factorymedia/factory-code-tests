# Technical Architecture Test

**This test is designed to assess the candidate’s skill and technique in producing software architecture design. It is not necessary to write actual code to complete this example. **

You should refrain from designing for a specific language/component, instead focusing on the technical requirements for design of the system as a whole. However, it is valid to make suggestions about the proposed technology choices we might use to implement your given solution.  

Using the following assumptions, please produce a process flow diagram for describing the following product:  

* The business has started to produce a lot of video assets. As a result, it has been decided that we would like to store all these videos online and make them available for web use.

* Since video costs money to encode and store, the business has decided additionally to create a simple cost logging system which tracks the uploads and attributes a cost against the user’s account. There will be 2 costs, one for the encode, and one for the storage. Later we may want to add a cost for delivery, but this is not part of the initial scope.

* You should describe the video upload and encode process. It is not necessary to describe the internals of the video encoding API. Consider this to be a black box that receives a video file as an input and returns a list of encoded file locations as an output (or may return an error).

* It is not necessary to describe the payment processing (e.g. gateway, card details etc). We are just interested in logging the cost against the account initially for later billing implementation.
