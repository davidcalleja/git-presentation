##  git checkout

	git checkout [-q] [-f] [-m] [<branch>]
	git checkout [-q] [-f] [-m] --detach [<branch>]
	git checkout [-q] [-f] [-m] [--detach] <commit>
	git checkout [-q] [-f] [-m] [[-b|-B|--orphan] <new_branch>] 
		[<start_point>]
	git checkout [-f|--ours|--theirs|-m|--conflict=<style>] 
		[<tree-ish>] [--] <paths>…​
	git checkout [-p|--patch] [<tree-ish>] [--] [<paths>…​]

Actualiza los ficheros existentes en el working tree con respecto al tree que hacemos referencia en el comando