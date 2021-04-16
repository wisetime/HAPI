The code reads the file names.txt from the folder c:/florin.
If you want to test it, either create the folder or change the code accordingly (to point to your own location).

This is how the output looks for the 20 names I included in the file.


17:12:52.848 INFO  ca.uhn.fhir.util.VersionUtil - HAPI FHIR version 4.2.0 - Rev 8491707942
17:12:52.857 INFO  ca.uhn.fhir.context.FhirContext - Creating new FHIR context for FHIR version [R4]
17:12:53.573 INFO  ca.uhn.fhir.util.XmlUtil - FHIR XML procesing will use StAX implementation 'Java Runtime Environment' version '1.8.0_171'
***********************************************************
*********  Running first test, use caching ****************
***********************************************************
	Searching for patient [SMITH]...  took 2321 ms
	Searching for patient [WASHINGTON]...  took 430 ms
	Searching for patient [JOHNSON]...  took 1563 ms
	Searching for patient [GRACIE]...  took 466 ms
	Searching for patient [BOLTON]...  took 393 ms
	Searching for patient [JOHNSTON]...  took 2505 ms
	Searching for patient [BRANDON]...  took 2077 ms
	Searching for patient [FRANK]...  took 2651 ms
	Searching for patient [LI]...  took 1766 ms
	Searching for patient [MARK]...  took 1354 ms
	Searching for patient [WANG]...  took 596 ms
	Searching for patient [HAMILTON]...  took 3128 ms
	Searching for patient [GORDON]...  took 2627 ms
	Searching for patient [ANDERSON]...  took 1063 ms
	Searching for patient [TAVARES]...  took 408 ms
	Searching for patient [MARNER]...  took 406 ms
	Searching for patient [CONNOR]...  took 2403 ms
	Searching for patient [MATT]...  took 2621 ms
	Searching for patient [MURRAY]...  took 1735 ms
	Searching for patient [ALBERT]...  took 407 ms
Average time for FIRST run is [1546] ms


***********************************************************
*********  Running second test, use caching ***************
***********************************************************
	Searching for patient [SMITH]...  took 1347 ms
	Searching for patient [WASHINGTON]...  took 257 ms
	Searching for patient [JOHNSON]...  took 984 ms
	Searching for patient [GRACIE]...  took 53 ms
	Searching for patient [BOLTON]...  took 52 ms
	Searching for patient [JOHNSTON]...  took 1569 ms
	Searching for patient [BRANDON]...  took 2155 ms
	Searching for patient [FRANK]...  took 1225 ms
	Searching for patient [LI]...  took 463 ms
	Searching for patient [MARK]...  took 380 ms
	Searching for patient [WANG]...  took 98 ms
	Searching for patient [HAMILTON]...  took 830 ms
	Searching for patient [GORDON]...  took 778 ms
	Searching for patient [ANDERSON]...  took 430 ms
	Searching for patient [TAVARES]...  took 55 ms
	Searching for patient [MARNER]...  took 63 ms
	Searching for patient [CONNOR]...  took 2594 ms
	Searching for patient [MATT]...  took 2928 ms
	Searching for patient [MURRAY]...  took 2531 ms
	Searching for patient [ALBERT]...  took 209 ms
Average time for SECOND run is [950] ms


***********************************************************
*********  Running third test, caching disabled ***********
***********************************************************
	Searching for patient [SMITH]...  took 2164 ms
	Searching for patient [WASHINGTON]...  took 408 ms
	Searching for patient [JOHNSON]...  took 1445 ms
	Searching for patient [GRACIE]...  took 465 ms
	Searching for patient [BOLTON]...  took 467 ms
	Searching for patient [JOHNSTON]...  took 2393 ms
	Searching for patient [BRANDON]...  took 2439 ms
	Searching for patient [FRANK]...  took 1896 ms
	Searching for patient [LI]...  took 1290 ms
	Searching for patient [MARK]...  took 1013 ms
	Searching for patient [WANG]...  took 416 ms
	Searching for patient [HAMILTON]...  took 1998 ms
	Searching for patient [GORDON]...  took 1833 ms
	Searching for patient [ANDERSON]...  took 655 ms
	Searching for patient [TAVARES]...  took 439 ms
	Searching for patient [MARNER]...  took 454 ms
	Searching for patient [CONNOR]...  took 1517 ms
	Searching for patient [MATT]...  took 2422 ms
	Searching for patient [MURRAY]...  took 2116 ms
	Searching for patient [ALBERT]...  took 437 ms
Average time THIRD run, caching disabled, is [1313] ms

