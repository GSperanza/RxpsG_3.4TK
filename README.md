# RxpsG_3.4TK
  
  First verify R is working properly on your PC.
  In Rstudio type  'version'  you should get something like:

    platform x86_64-pc-linux-gnu
    arch x86_64
    os linux-gnu
    system x86_64, linux-gnu
    status
    major 4
    minor 3.1
    year 2024
    month 06
    day 16
    svn rev 84548
    language R
    version.string R version 4.3.1 (2023-06-16) nickname Beagle Scouts

RxpsG installation:

    In the "Manual and Tar-gz" repository of this site select and click on the 
    RxpsG_xx.xx.tar.gz package and download. Exit the unzipping procedure if it 
    starts automatically.

    Control in the Downloads folder the RxpsG_xx.xx.tar.gz package is present 
    (it could be the .gz extension is lacking do not worry).

    Run RStudio

    In RStudio copy and paste the following command to INSTALL THE REQUIRED LIBRARIES:

    install.packages(c("digest", "import", "latticeExtra", "minpack.lm", "signal", "SparseM"), repos = "https://cloud.r-project.org", dependencies=TRUE)

    Control that installation proceeds correctly without errors;
    
    Some options of RxpsG (Automatic Element recognition, Wavelets filtering, Model Fitting) 
    require the installation of the additional packges: baseline, FME, rootSolve, wavelets. 
    If interested copy and paste the following command:
    
    install.packages(c("baseline", "FME", "rootSolve", "wavelets", repos = "https://cloud.r-project.org", dependencies=TRUE)


    To INSTALL RxpsG_3.4 copy and paste the following command:

    install.packages("C:/Path-To-Tar.Gz/RxpsG_3.4.tar.gz", type = "source", dependencies=TRUE)

    where Path-To-Tar.Gz is the path to the dowloaded RxpsG_3.4.tar.gz file.

    N.B. if installation blocks at level:
         '** testing if installed package can be loaded from temporary location '
         control if behind the RStudio window a GUI is waiting for your response

To run RxpsG, in RStudio select the PACKAGE pain (generally on the right of the RStudio console) and select the RxpsG package. This should automatically load and run the software.
The command   'xps()'   also starts the RxpsG program.

This program is free software. You can use it under the terms of the GNU General Public License. http://www.gnu.org/licenses/ and licenses linked to the use of the R, Rstudio platforms.

-----

Authors decline any responsibility deriving from the use of the software or from software bugs.

Users are kindly requested to cite the software authors in their publications:

Giorgio Speranza, Roberto Canteri 
Fondazione Bruno Kessler, 
Sommarive str. 18 38123 Trento Italy. 
Email: speranza@fbk.eu


Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
Attach files by dragging & dropping, selecting or pasting them.
