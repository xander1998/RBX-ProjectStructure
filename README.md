# Roblox Studio Project Folder Template

World: -> Environment : Objects & assets such as nature, vegetation, lighting, hills, mountains, terrain, backgrounds
	   -> Structures : Things such as buildings, bridges, and things that are classed as structures in general.
	   -> Sounds : Sounds that can be heard locally [only by the current player] or globally [everyone].

ReplicatedStorage: -> Classes : Here you can put modules that can create instances such as tables & utilities, 
				   and other things on the client.
				   -> Events : You can place RemoteEvents in here.
                   -> Components : A storage area that can be shared with the server/client.
				   		-> Gui : A storage area for guis.
				   		-> Objects : A storage area for objects/assets.
				   		-> Sounds : A storage area for sounds.
				   		-> Particles : A storage area for particles/effects.
				   -> Functions : You can place RemoteFunctions in here.
				   -> Modules : Utility modules that can be used by the client. [OPTIONAL:] You can make a Shared folder 
				   that can be used by both the Server and the Client.
				   
ServerScriptService: -> Core - Modules : Modules that can be used by the server scripts.
					 -> Core - Scripts : Location of all the server scripts.
					 
ServerStorage: -> Classes : You can put modules for creating classes such as tables, data, utilities that can be used by server scripts.
			   -> Events : You can place BindableEvents in here.
			   -> Functions : You can place BindableFunctions in here.
			   -> Misc : General storage for things you use.
			   -> Modules : Utility modules that can be used by server scripts.
			   
StarterPlayerScripts: -> Core : A place for LocalScripts.
					  -> UI : A place for LocalScripts that control the UI.