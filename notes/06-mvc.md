# MVC
for controller services and appstate you should use a plural version to know the distinction between the model
start with model then the appstate then controller then services then connect the app.js to the controller 
for controller you put your draw functions but for a template you can put that in the model
to grab the variables from the appstate you would do 
draw____(){
  let ____ = appState.______
  let template = ''
  ____.foreach(i=> template += i.name)
  setHTML('id',template)-------> this is a utility function to shorten a document.getElementbyId function
}-----> also make sure your id is the same

for putting a template inside a model you would use the word get

when connecting a new controller to a HTML always start with a console.log to see if its connected

