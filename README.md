**async_abc_transport**: Async abstract transport module for import in to project as a AbstractConnectorAsync class. Useful in cases where you have many different messangers clients and one or more others logic instances to connect all together.
# Architecture

# /abc_handler 
Module with async abstract class transport with handlers. Based on Redis Async for queues on receive, send methods. Packed in docker instances. 
- **abc_handler**: Abstract Base Classes directory for handling messages and connections.
    - **__init__.py**: Initialization file for the Python package.
    - **abc_async_transport.py**: Defines the `AbstractConnectorAsync` class for all connectors.
    - **config_queue.py**: Defines queues to listen in the `AbstractConnectorAsync` class for all connectors.
    - **handlers.py**: Contains handler classes for processing messages.# async_abc_transport
# async_abc_transport
# async_abc_transport
