# GitRESTAPI

This code is for an iOS application that interacts with the Github API to fetch and create Gists.

The AppDelegate class conforms to the UIApplicationDelegate protocol and sets up the basic app configuration, including customization of the launch sequence.

The DataService class defines functions to fetch, create, and star/unstar Gists by creating and sending requests to the Github API. The Gist and File structs define the structure of the data returned by the API and the ViewController class serves as the main view controller for the app, displaying a table view with the fetched Gists and allowing users to create new Gists, as well as star and unstar existing ones.

The code makes use of URLComponents to create and manage the URLs needed for interacting with the Github API and uses URLSession to create and send requests. The data returned by the API is parsed and decoded using JSONDecoder and the app communicates with the user using UIAlertControllers.
