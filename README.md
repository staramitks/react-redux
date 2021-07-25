# react-redux
Repo for react redux project
# key concepts
 - store :- For keeping state
 - action :- To describe action - describe desired change of state
 - reducer :- apply action impact - Carries out state transition

 # Principles
  - The state of application is stored in a single object tree within a single store
  - The only way to change the state is to emit an action, an object desribing what happened - for e.g. type - BUY_CAKE
  - To specify the state tree is transformed by actions, you write pure reducers.