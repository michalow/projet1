<<<<<<< HEAD
Och te swinie, to brudni ludzie,
=======
Ach ci ludzie, to brudne swinie,
>>>>>>> main
Co napletli o mojej dziewczynie,
Jakies bzdury o jej nalogach,
To po prmtion@FRPXXXXX MINGW64 ~/Desktop/projet1
$ cd

Formation@FRPXXXXX MINGW64 ~
$ git clone git@github.com:monDossierhttps://github.com/michalow/projet1.git
Cloning into 'projet1'...
fatal: protocol 'git@github.com:monDossierhttps' is not supported

Formation@FRPXXXXX MINGW64 ~
$ git clone https://github.com/michalow/projet1.git
Cloning into 'projet1'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

Formation@FRPXXXXX MINGW64 ~
$ pwd
/c/Users/Formation

Formation@FRPXXXXX MINGW64 ~
$ cd projet1

Formation@FRPXXXXX MINGW64 ~/projet1 (main)
$ pwd
/c/Users/Formation/projet1

Formation@FRPXXXXX MINGW64 ~/projet1 (main)
$ ls
README.md

Formation@FRPXXXXX MINGW64 ~/projet1 (main)
$ touch test1.txt

Formation@FRPXXXXX MINGW64 ~/projet1 (main)
$ ls
README.md  test1.txt

Formation@FRPXXXXX MINGW64 ~/projet1 (main)
$ cd

Formation@FRPXXXXX MINGW64 ~
$ pwd
/c/Users/Formation

Formation@FRPXXXXX MINGW64 ~
$ cd Desktop/

Formation@FRPXXXXX MINGW64 ~/Desktop
$ ls
 algorithme/   diff.PNG       exercice_GIT_J1.pdf   Git/     'git commit message oublie.PNG'  'Microsoft Edge.lnk'*   python/             'Visual Studio Code.lnk'*
  desktop.ini   Discord.lnk*   formations/          'Git 2'/   Google Chrome.lnk*               projet1/               TP_git_conflit.pdf

  Formation@FRPXXXXX MINGW64 ~/Desktop
  $ cd projet1

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1
  $ git clone https://github.com/michalow/projet1.git
  Cloning into 'projet1'...
  remote: Enumerating objects: 3, done.
  remote: Counting objects: 100% (3/3), done.
  remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
  Receiving objects: 100% (3/3), done.

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1
  $ git init
  Initialized empty Git repository in C:/Users/Formation/Desktop/projet1/.git/

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (master)
  $ git add .
  warning: adding embedded git repository: projet1
  hint: You've added another git repository inside your current repository.
  hint: Clones of the outer repository will not contain the contents of
  hint: the embedded repository and will not know how to obtain it.
  hint: If you meant to add a submodule, use:
  hint: 
  hint:   git submodule add <url> projet1
  hint: 
  hint: If you added this path by mistake, you can remove it from the
  hint: index with:
  hint: 
  hint:   git rm --cached projet1
  hint: 
  hint: See "git help submodule" for more information.

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (master)
  $ ls
  projet1/

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (master)
  $ rm dir/projet1
  rm: cannot remove 'dir/projet1': No such file or directory

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (master)
  $ ls
  projet1/

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (master)
  $ rm projet1
  rm: cannot remove 'projet1': Is a directory

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (master)
  $ rm projet/
  rm: cannot remove 'projet/': No such file or directory

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (master)
  $ git rm -r projet/
  fatal: pathspec 'projet/' did not match any files

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (master)
  $ git rm -r projet1/
  fatal: could not lookup name for submodule 'projet1'

  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (master)
  $
   *  History restored 


   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
   $ ls
   README.md

   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
   $ git status
   On branch main
   Your branch is up to date with 'origin/main'.

   Changes not staged for commit:
     (use "git add <file>..." to update what will be committed)
       (use "git restore <file>..." to discard changes in working directory)
               modified:   README.md

	       no changes added to commit (use "git add" and/or "git commit -a")

	       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
	       $ git add .

	       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
	       $ git commit -m "modif README.md"
	       [main 4241cf2] modif README.md
	        1 file changed, 1 insertion(+), 1 deletion(-)

		Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		$ git push 
		Enumerating objects: 5, done.
		Counting objects: 100% (5/5), done.
		Writing objects: 100% (3/3), 256 bytes | 256.00 KiB/s, done.
		Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
		To https://github.com/michalow/projet1.git
		   ced8c0f..4241cf2  main -> main

		   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		   $ git status
		   On branch main
		   Your branch is up to date with 'origin/main'.

		   nothing to commit, working tree clean

		   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		   $ git branch
		   * main

		   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		   $ branch branche1
		   bash: branch: command not found

		   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		   $ git branch branche1

		   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		   $ git branch
		     branche1
		     * main

		     Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		     $ git checkout -b
		     error: switch `b' requires a value

		     Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		     $ git checkout -b branche1
		     fatal: a branch named 'branche1' already exists

		     Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		     $ git checkout branch -b branche1
		     fatal: 'branch' is not a commit and a branch 'branche1' cannot be created from it

		     Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		     $ git status
		     On branch main
		     Your branch is up to date with 'origin/main'.

		     nothing to commit, working tree clean

		     Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		     $ git branch
		       branche1
		       * main

		       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		       $ ls -a
		       ./  ../  .git/  README.md

		       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		       $ git checkout projet1
		       error: pathspec 'projet1' did not match any file(s) known to git

		       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		       $ git branch projet1

		       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		       $ git branch branche1
		       fatal: a branch named 'branche1' already exists

		       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
		       $ git branch -a
		         branche1
			 * main
			   projet1
			     remotes/origin/HEAD -> origin/main
			       remotes/origin/main

			       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
			       $ git checkout projet1
			       Switched to branch 'projet1'

			       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (projet1)
			       $ git checkout branche1
			       Switched to branch 'branche1'

			       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
			       $ git branch -d projet1
			       Deleted branch projet1 (was 4241cf2).

			       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
			       $ git branch
			       * branche1
			         main

				 Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
				 $ ls
				 README.md

				 Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
				 $ add .
				 bash: add: command not found

				 Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
				 $ git add .

				 Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
				 $ git status
				 On branch branche1
				 Changes to be committed:
				   (use "git restore --staged <file>..." to unstage)
				           modified:   README.md


					   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
					   $ git commit -m "ajout 2ème ligne"
					   [branche1 3796225] ajout 2ème ligne
					    1 file changed, 2 insertions(+), 1 deletion(-)

					    Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
					    $ git diff

					    Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
					    $ git log
					    commit 3796225467d9affed1532bb46045b5f981fe4e61 (HEAD -> branche1)
					    Author: michalow <michalowska.natalia@gmail.com>
					    Date:   Thu Oct 13 16:10:59 2022 +0200

					        ajout 2ème ligne

						commit 4241cf27ad7070132a4080ee3a3a1358df6038a6 (origin/main, origin/HEAD, main)
						Author: michalow <michalowska.natalia@gmail.com>
						Date:   Thu Oct 13 15:41:47 2022 +0200

						    modif README.md

						    commit ced8c0f146bf06d3c221c35a53a0e2e9fe22c9f7
						    Author: michalow <michalowska.natalia@gmail.com>
						    Date:   Thu Oct 13 15:08:37 2022 +0200

						        Initial commit

							Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
							$ git branch
							* branche1
							  main

							  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
							  $ git checkout main
							  Switched to branch 'main'
							  Your branch is up to date with 'origin/main'.

							  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
							  $ git checkout -b branche2
							  Switched to a new branch 'branche2'

							  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
							  $ git branch
							    branche1
							    * branche2
							      main

							      Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
							      $ git checkout -b main
							      fatal: a branch named 'main' already exists

							      Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
							      $ git checkout main
							      Switched to branch 'main'
							      Your branch is up to date with 'origin/main'.

							      Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
							      $ git checkout branche1
							      error: Your local changes to the following files would be overwritten by checkout:
							              README.md
								      Please commit your changes or stash them before you switch branches.
								      Aborting

								      Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
								      $ git add .

								      Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
								      $ git commit -m "changement de texte README"
								      [main d8190e7] changement de texte README
								       1 file changed, 8 insertions(+), 1 deletion(-)

								       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
								       $ git push
								       Enumerating objects: 5, done.
								       Counting objects: 100% (5/5), done.
								       Delta compression using up to 8 threads
								       Compressing objects: 100% (2/2), done.
								       Writing objects: 100% (3/3), 445 bytes | 445.00 KiB/s, done.
								       Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
								       To https://github.com/michalow/projet1.git
								          4241cf2..d8190e7  main -> main

									  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
									  $ git branch branche1
									  fatal: a branch named 'branche1' already exists

									  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (main)
									  $ git checkout branche1
									  Switched to branch 'branche1'

									  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
									  $ git add .

									  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
									  $ git commit -m "modification README"
									  [branche1 9997e1e] modification README
									   1 file changed, 8 insertions(+), 2 deletions(-)

									   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche1)
									   $ git checkout branche2
									   Switched to branch 'branche2'

									   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
									   $ git add 
									   Nothing specified, nothing added.
									   hint: Maybe you wanted to say 'git add .'?
									   hint: Turn this message off by running
									   hint: "git config advice.addEmptyPathspec false"

									   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
									   $ git add 
									   Nothing specified, nothing added.
									   hint: Maybe you wanted to say 'git add .'?
									   hint: Turn this message off by running
									   hint: "git config advice.addEmptyPathspec false"

									   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
									   $ git add .

									   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
									   $ git commit -m "modification2"
									   [branche2 b8ab61e] modification2
									    1 file changed, 8 insertions(+), 1 deletion(-)

									    Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
									    $ git add .

									    Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
									    $ git push
									    fatal: The current branch branche2 has no upstream branch.
									    To push the current branch and set the remote as upstream, use

									        git push --set-upstream origin branche2

										To have this happen automatically for branches without a tracking
										upstream, see 'push.autoSetupRemote' in 'git help config'.


										Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
										$ git branche
										git: 'branche' is not a git command. See 'git --help'.

										The most similar command is
										        branch

											Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
											$ git branch
											  branche1
											  * branche2
											    main

											    Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
											    $ git merge main
											    Auto-merging README.md
											    CONFLICT (content): Merge conflict in README.md
											    Automatic merge failed; fix conflicts and then commit the result.

											    Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2|MERGING)
											    $ git status
											    On branch branche2
											    You have unmerged paths.
											      (fix conflicts and run "git commit")
											        (use "git merge --abort" to abort the merge)
												  Eh te barany, to nie swinie,                        |  la la la                                             |  Ach ci ludzie, to brudne swinie,
												    Co napletli o mojej dziewczynie,                    |  -----------------------------------------------------|  Co napletli o mojej dziewczynie,
												      Eh te barany, to nie swinie,                        |  la la la                                             |  Ach ci ludzie, to brudne swinie,
												        Co napletli o mojej dziewczynie,                    |  -----------------------------------------------------|  Co napletli o mojej dziewczynie,
													  Eh te barany, to nie swinie,                        |  la la la                                             |  Ach ci ludzie, to brudne swinie,
													    Co napletli o mojej dziewczynie,                    |  -----------------------------------------------------|  Co napletli o mojej dziewczynie,

													    Unmerged paths:
													      (use "git add <file>..." to mark resolution)
													              both modified:   README.md

														      no changes added to commit (use "git add" and/or "git commit -a")

														      Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2|MERGING)
														      $ git mergetool

														      This message is displayed because 'merge.tool' is not configured.
														      See 'git mergetool --tool-help' or 'git help config' for more details.
														      'git mergetool' will now attempt to use one of the following tools:
														      opendiff kdiff3 tkdiff xxdiff meld tortoisemerge gvimdiff diffuse diffmerge ecmerge p4merge araxis bc codecompare smerge emerge vimdiff nvimdiff
														      Merging:
														      README.md

														      Normal merge conflict for 'README.md':
														        {local}: modified file
															  {remote}: modified file
															  Hit return to start merge resolution tool (vimdiff):
															  4 fichiers à éditer

															  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2|MERGING)
															  $ git add .

															  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2|MERGING)
															  $ git commit -m "conflit resolu"
															  [branche2 9c920c5] conflit resolu

															  Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
															  $ git push
															  fatal: The current branch branche2 has no upstream branch.
															  To push the current branch and set the remote as upstream, use

															      git push --set-upstream origin branche2

															      To have this happen automatically for branches without a tracking
															      upstream, see 'push.autoSetupRemote' in 'git help config'.


															      Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
															      $ git push --set-upstream origin branche2
															      Enumerating objects: 10, done.
															      Counting objects: 100% (10/10), done.
															      Delta compression using up to 8 threads
															      Compressing objects: 100% (5/5), done.
															      Writing objects: 100% (6/6), 747 bytes | 747.00 KiB/s, done.
															      Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
															      remote: Resolving deltas: 100% (1/1), done.
															      remote: 
															      remote: Create a pull request for 'branche2' on GitHub by visiting:
															      remote:      https://github.com/michalow/projet1/pull/new/branche2
															      remote:
															      To https://github.com/michalow/projet1.git
															       * [new branch]      branche2 -> branche2
															       branch 'branche2' set up to track 'origin/branche2'.

															       Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
															       $ git branch
															         branche1
																 * branche2
																   main

																   Formation@FRPXXXXX MINGW64 ~/Desktop/projet1 (branche2)
																   $ git checkout branche1
																   Switched to branch 'branche1'
																     Och te swinie, to brudni ludzie,                    |  la la la                                             |  Ach ci ludzie, to brudne swinie,
																       Co napletli o mojej dziewczynie,                    |  -----------------------------------------------------|  Co napletli o mojej dziewczynie,
																         Jakies bzdury o jej nalogach,                       |  -----------------------------------------------------|  Jakies bzdury o jej nalogach,
																	   To po prostu litosc i trwoga.                       |  -----------------------------------------------------|  To po prostu litosc i trwoga.
																	     Tak to bywa gdy ktos zazdrosci,                     |  -----------------------------------------------------|  Tak to bywa gdy ktos zazdrosci,
																	       Kiedy brak mu wlasnej milosci,                      |  -----------------------------------------------------|  Kiedy brak mu wlasnej milosci,
																	         Plotki plodzi, mnie nie zaszkodzi zadne obce zlo    |  -----------------------------------------------------|  Plotki plodzi, mnie nie zaszkodzi zadne obce zlo    
																		   Na moj sposob widziec ja...                         |  -----------------------------------------------------|  Na moj sposob widziec ja...
																		     ----------------------------------------------------|  -----------------------------------------------------|  ----------------------------------------------------  ----------------------------------------------------|  -----------------------------------------------------|  ----------------------------------------------------<EADME_LOCAL_1529.md [dos] (16:47 13/10/2022)8,16 Tout ./README_BASE_1529.md [unix] (16:47 13/10/2022)1,9 Tout <ADME_REMOTE_1529.md [dos] (16:47 13/10/2022)8,16 Tout  <<<<<<< HEAD
																		       Och te swinie, to brudni ludzie,
																		         =======
																			   Ach ci ludzie, to brudne swinie,
																			     >>>>>>> main
																			       Co napletli o mojej dziewczynie,
																			         Jakies bzdury o jej nalogach,
																				   To po prostu litosc i trwoga.
																				     Tak to bywa gdy ktos zazdrosci,
																				       Kiedy brak mu wlasnej milosci,
																				         Plotki plodzi, mnie nie zaszkodzi zadne obce zlo
																					   Na moj sposob widziec ja...
																					   ~
																					   ~
																					   ~
																					   ~
																					   ~
																					   ~
																					   ~
																					   ~
																					   README.md [dos] (16:47 13/10/2022)                                                                                                                          8,16 Toutwqiwq
																					   tistu litosc i trwoga.
Tak to bywa gdy ktos zazdrosci,
Kiedy brak mu wlasnej milosci,
Plotki plodzi, mnie nie zaszkodzi zadne obce zlo
Na moj sposob widziec ja...
