# Undergraduate Thesis's Documentation Repository
---

#### The Author
*Ronauli Silva N. S. - 5113100142*
*Informatics Engineering Department, Information Technology Faculty*
*Institut Teknologi Sepuluh Nopember, Soerabadja*
*contact at : ronayumik@gmail.com*
---
## TLDR
Intended to make my thesis documentations easier to handle, version control & integrated at ease.

## Highlights
- Using Latex both paper and the thesis's book
- PPT are kids-world themed, would you like to see and send me feedbacks? :)
- will be completed later.

### Latex Instalation
   * Install tex-live
      
      ```
      $ sudo apt-get update
      $ sudo apt-get install texlive-full
      ```

         * Install tex-studio

	    ```
	       $ sudo apt-get install texstudio
	          ```
		     
		        * You need to install windows fonts

			   ```
			      $ sudo apt-get install ttf-mscorefonts-installer
			         $ sudo fc-cache -f -v
				    ```

				       * Open texstudio.
				          * Open texstudio configuration in `option` menu
					     * In tab `build`, choose `xelatex` as default compiler
					        * Open tab `command`, set `xelatex -synctex=1 -interaction=nonstopmode --shell-escape %.tex` as xelatex command.
						   * Install python-pygments
						      
						         ```
							    $ sudo apt-get install python-pygments
							       ```

							          * Run `build & view` to compile.

								     ```
								        $ sudo apt-get install python-pygments
									   ```

									      * Run `build & view` to compile.

									      ## Note: If you have problem with section numbering (section number doesn't appear), run this command:

									      ```
									      $ sudo wget http://mirrors.ctan.org/macros/latex/contrib/titlesec/titlesec.sty -O /usr/share/texlive/texmf-dist/tex/latex/titlesec/titlesec.sty
									      ```
									        - 
										  


										  #### Acknowledgement
										  Only to be copied as a academic reference , not to be copied in commercial purpose. 
										  You should know law & legal enforcements for copyrights and you cannot blame me for anything I sue you in the future related to the acknowledgements from this repository. Hasta lavista!
