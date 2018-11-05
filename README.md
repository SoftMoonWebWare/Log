# Log
groups related UI event logs together in logging output for easier debugging.

Supports console.log as well as in-document logging and extro-document logging.

Often a stream of UI events (mouse or keyboard) happens so quick, if your event handlers each log something, it is hard to go back and relate each log to a handler and an individual user-action such as typing a key or moving a mouse.  This will group events that occur quikly into a "user-action".
