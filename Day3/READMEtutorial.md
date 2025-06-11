Unable to create process using 'C:\Users\Parijaat Gaur\anaconda3\python.exe "C:\Users\Parijaat Gaur\anaconda3\Scripts\conda-script.py" shell.powershell activate "C:\Users\Parijaat Gaur\anaconda3"'
Invoke-Expression : Cannot bind argument to parameter 'Command' because it is an empty string.
At C:\Users\Parijaat Gaur\anaconda3\shell\condabin\Conda.psm1:76 char:36
+         Invoke-Expression -Command $activateCommand;
+                                    ~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidData: (:) [Invoke-Expression], ParameterBindingValidationException
    + FullyQualifiedErrorId : ParameterArgumentValidationErrorEmptyStringNotAllowed,Microsoft.PowerShell.Commands.Invo
   keExpressionCommand

PS C:\Users\Parijaat Gaur> python
Python 3.11.9 (tags/v3.11.9:de54cf5, Apr  2 2024, 10:12:12) [MSC v.1938 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> ^Tgist
  File "<stdin>", line 1
    gist
    ^
SyntaxError: invalid non-printable character U+0014
>>> pip install numpy
  File "<stdin>", line 1
    pip install numpy
