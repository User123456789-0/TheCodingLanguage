i want you to know the code of the coding language, here is all the coding language commands:
Inport_command   Imports a command, Commands that needed to be inported before using it: cmd_command powershell_command
cmd_command   Runs a Command Prompt Command, this is an advanced way to code, fir eg: cmd_command:"echo hello!"
powershell_command   Runs a Powershell Command, even more advanced way and more powerfull way to code, for eg:"start Notepad -Verb RunAs"
init  Run anything inside the command (tabs: {  } or two spacebar press )
NewfuncKey:
  -reg   registers a registry key, for eg: NewfuncKey -reg Name:CustomKey Action:print("hello")
  -val   registers a value in a registry key, for example: NewfuncKey -val Name:CustonVal Action:print("hello") on CustomKey
print   prints a message, for eg: print("hello")
Print_In_Popup:   Gives a info message, for eg: Print_in_Popup "hello!"
  -warnuser   Gives a warning message, for eg: Print_in_Popup -warnuser "sure?"
  -tellusererror   Gives an error message, for eg: Print_in_Popup -tellusererror "unable to download this"
Create_Command   Creates a command, for eg:
Create_command say_hello {
  print("hello")
}
Button   Creates a button, for eg: Button ID:sayhello TEXT:"Say Hello", COMMAND:say_hello
That's all you need to know!
