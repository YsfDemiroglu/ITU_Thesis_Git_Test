# ITU_Thesis_Git_Test

% ----------------------------------------------------------------- %
% Please visit the following page for the current version:		    %
% https://github.com/ondes/Template-Latex-ITU-Thesis   				%
% ----------------------------------------------------------------- %

% ----------------------------------------------------------------- %
% 					DOCUMENT CLASS ARGUMENTS 						%
% [onluarkali,tekyonlu],             							    %
% [turkce,ingilizce],             							    	%
% [lisans,yukseklisans,doktora],             					    %
% [bez,karton],					    								%
% [bilisim,fenbilimleri,sosyalbilimler,avrasya,enerji]			   	%
% ----------------------------------------------------------------- %
% Sample use: \documentclass[onluarkali,ingilizce,yukseklisans,    	%
% karton,fenbilimleri]{itutez}					  				   	%
% Other sample use: \documentclass[tekyonlu,ingilizce,	           	%
% yukseklisans,bez,bilisim]{itutez}			           			   	%
% ----------------------------------------------------------------- %
% 					TANIMLAMALAR/DEFINITIONS						%
% onluarkali: twoside                     			  			   	%
% tekyonlu: oneside						 						   	%
% turkce: turkish						 						   	%
% ingilizce: english											   	%
% lisans: undergraduate												%
% yukseklisans: masters											   	%
% doktora: phd							  						   	%
% bez: hardcover version					  					    %
% karton: paperback version					  					    %
% 					INSTITUES (For grad students)					&
% bilisim: informatics						  					    %
% fenbilimleri: science and technology							    %
% sosyalbilimler: social sciences				 				    %
% avrasya: eurasia						 						    %
% enerji: energy						   						    %
% 					FACULTIES (For undergrads)						%
% ucakuzay: aeronautics & astronautics 								%
% elektrikelektronik: electrical and electronics				    %
% ----------------------------------------------------------------- %
% !! The following faculties will be added to the class file !!     %
% ----------------------------------------------------------------- %
% insaat: civil														%	
% mimarlik: architecture											%
% makina: mechanical												%
% denizcilik: maritime												%
% kimyametalurji: chemical-metallurgical							%
% isletme: management												%
% tekstiltek: textile tech											%
% maden: mines														%
% gemiinsaati: naval architecture									%
% bilgisayarbilisim: computer & informatics							%
% fenedebiyat: science & letters									%
% ----------------------------------------------------------------- %


% ----------------------------------------------------------------- %
% Pay attention to letter case. The structure is case sensitive     %
% {Name}{SURNAME} means first letter of name is capital and that    %
% all letters of surname are capital.                               %
% ----------------------------------------------------------------- %

% ----------------------------------------------------------------- %
% No titles, only Name and SURNAME must be written.      	        %
% ----------------------------------------------------------------- %

%\yazar{Name}{SURNAME}
%\ogrencino{101010101}

% ----------------------------------------------------------------- %
% If you do not use the structure, do not delete it. Just delete    %
% the argument. \unvan{} means title.                               %
% ----------------------------------------------------------------- %

%\unvan{(Any Profession)}
 
% ----------------------------------------------------------------- %
% For below, the first argument for Turkish, the second is for      %
% English.       						   						    %
% ----------------------------------------------------------------- %

% ----------------------------------------------------------------- %
% Only the first letters of words must be capital.		     	    %
% ----------------------------------------------------------------- %

%\anabilimdali{Elektrik Mühendisliği Anabilim Dalı}{Department of Electrical Engineering}
%\programi{Elektrik Mühendisliği Programı}{Electrical Engineering Programme}

% ----------------------------------------------------------------- %
% For paperback version, the submission date to the faculty. For    %
% hardcover (indigo/black) version, date of defense.		   	    %
% ----------------------------------------------------------------- %

%\tarih{TEZİN SAVUNULDUĞU AY YIL}{MONTH YEAR OF DEFENSE}
%\tarihKucuk{Tezin savunulduğu ay yıl}{Month year of defense}

% ----------------------------------------------------------------- %
% Thesis advisor, title, thesis submission date, defense date       %
% ----------------------------------------------------------------- %

%\tezyoneticisi{Prof. Dr. Name SURNAME}{Istanbul Technical University}   

%\baslik{TEZ BAŞLIĞI BURAYA GELİR}
%{GEREKLİ İSE İKİNCİ SATIR}
%{GEREKLİ İSE ÜÇÜNCÜ SATIR, ÜÇ SATIRA SIĞDIRINIZ}

%\title{THESIS TITLE HERE}
%{SECOND LINE IF NECESSARY}
%{THIRD LINE IF NECESSARY, FIT TITLE IN THREE LINES}

% ----------------------------------------------------------------- %
% The date of submission of the paperback to the department.	    %
% ----------------------------------------------------------------- %

%\tezvermetarih{1 Mayıs 2020}{1 May 2020} 

%\tezsavunmatarih{1 Haziran 2020}{1 June 2020}

% ----------------------------------------------------------------- %
% coadvisor and jury information. If you do not use all items,     	%
% leave the corresponding arguments blank such as                  	%
% \esdanismani{}{} 					           						%
% ----------------------------------------------------------------- %

%\esdanismani{Prof. Dr. Name SURNAME}{Istanbul Technical University}   

%\juriBir{Prof. Dr. Name SURNAME}{Middle East Technical University}  

%\juriIki{Prof. Dr. Name SURNAME}{Boğaziçi University}  

%\juriUc{Prof. Dr. Name SURNAME}{Bilkent University}  

%\juriDort{Prof. Dr. Name SURNAME}{Sabancı University}  

%\juriBes{Prof. Dr. Name SURNAME}{Koç University}

% ----------------------------------------------------------------- %
% Packages and definitions to be used are given in the following    %
% ----------------------------------------------------------------- %

%\input{defs}                                        

% ----------------------------------------------------------------- %
% For dedication page. Leave the argument blank if not used.	    %
% ----------------------------------------------------------------- %

%\ithaf{To my family,}

% ----------------------------------------------------------------- %
% Form the below files						   					    %
% ----------------------------------------------------------------- %

%\kisaltmalistesi{\input{abbreviations}}
%\sembollistesi{\input{symbols}}

%\onsoz{\input{foreword}}             
%\ozet{\input{summary_TR}}               
%\summary{\input{summary}}             

%\begin{document}

% ----------------------------------------------------------------- %
% Also form the below files. All corresponding inputs should point  %
% to a file. They are provided inside the archive.                  %
% ----------------------------------------------------------------- %

%\input{chapter_01}                                       
%\input{chapter_02}
%\input{chapter_03}
%\input{chapter_04}
%\input{chapter_05}
%\input{chapter_06}

% ----------------------------------------------------------------- %
% Form thesis_bib.bib to contain your references in bibtex format   %
% use \cite command for citing your references.                     %
% ----------------------------------------------------------------- %

%\bibliographystyle{thesis_itubib}      % Designed .bst file 
%\bibliography{thesis_bib}			   % .bib file

% ----------------------------------------------------------------- %
% Appendix files. appendices_cover is the appendix title page.      %
% ----------------------------------------------------------------- %

%\eklerkapak{}
%\input{appendices_cover}

% ----------------------------------------------------------------- %
% \eklerbolum{x} forms and appendix of x chapters. 				    %
% ----------------------------------------------------------------- %

%\eklerbolum{0}
%\input{appendices}

% ----------------------------------------------------------------- %
% The summary page                                                  %
% ----------------------------------------------------------------- %

%\ozgecmis{\input{resume}} % Edge (Sırt) of the thesis at the very end.
%\end{document}                      

% ----------------------------------------------------------------- %
% Updated voluntarily by	  :										%
% E. Baris Ondes    : ondes@itu.edu.tr 	  OR ondesalt@pm.me			% 
% Tamer Sener	    : senerta@itu.edu.tr  OR senertam@pm.me			%
% Berkan Kacmaz	    : kacmazb@itu.edu.tr  OR kacmazberkan0@gmail.com%
% S. Baris Ozturk   : ozturksb@itu.edu.tr OR salihbaris@gmail.com   %
% O. Ozgun Altunkaya: altunkayao@itu.edu.tr OR ozgun@pm.me 			%
% Latest update: 22-Feb-2021										%
% ----------------------------------------------------------------- %
