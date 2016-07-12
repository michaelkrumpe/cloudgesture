# cloudgesture
Blocky UI to Cloud Orchestrators

Goal is to create a Blocky code interface to the cloud orchestration workflow engines such as salt, chef and puppet. Each of these orchestrators have a barrier to the market as many IT Administrators are not Developers. Utilizing the Blocky project from Google, which is typically utilized in interfaces to teach children and adults how to "code", and it will generate useful code like javascript, arduino code, etc, why not adapt it in a way so that the code needed for the rules engines of these cloud orchestrators could also come from Blocky as a source. 

Targeting workflow event rules engines in these platforms, non-developers could use cloudgesture to make changes to workflows easily, and/or create new workflows inot the system. 

#R&D Phases
1. Proof of Concept - show that Blocky can generate code as needed to be understood by a configuration and automation engine (i.e. Salt Stack)
2. Create UI Portal to maintain users, and saving of Blocky code 
3. Git repo of Blocky code
3. Authentication and integration methods with the Orchestrator over API, to then upload/inject Blocky generated code


#References
Google Blocky https://developers.google.com/blockly/

Salt Stack 
Events Engine https://docs.saltstack.com/en/latest/topics/event/events.html#from-python

Puppet
Application Workflow https://docs.puppet.com/pe/latest/app_orchestration_workflow.html

Chef
Automate https://www.chef.io/automate/

