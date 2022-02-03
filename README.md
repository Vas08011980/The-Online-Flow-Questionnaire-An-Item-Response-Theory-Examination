# The-Online-Flow-Questionnaire-An-Item-Response-Theory-Examination
The Online Flow Questionnaire: An Item Response Theory Examination
Project:
    Name = The-Online-Flow-Questionnaire-An-Item-Response-Theory-Examination;

Data:
    File = .\The-Online-Flow-Questionnaire-An-Item-Response-Theory-Examination.ssig;

Analysis:
    Name = Test1;
    Mode = Calibration;

Title:
https://github.com/Vas08011980/BMC-Psychology-https-github.com-Vas08011980-The-Online-Flow-Questionnaire-An-Item-Response-Theory-/commit/d651a65a3680d0e1cf72af15667b34736e0ba40c
Comments:
Estimation:
    Method = BAEM;
    E-Step = 500, 1e-005;
    SE = S-EM;
    M-Step = 50, 1e-006;
    Quadrature = 49, 6;
    SEM = 0.001;
    SS = 1e-005;

Scoring:
    ID = ID;
    Create SS to SC table;
    Mean = 0;
    SD = 1;

Miscellaneous:
    Decimal = 2;
    Processors = 4;
    Print M2, StdRes, CTLD, GOF, Loadings, P-Nums, Diagnostic;
    Min Exp = 1;

Groups:

Group :
    Dimension = 1;
    Items = Flow1, Flow2, Flow3, Flow4, Flow5;
    Codes(Flow1) = 0(0), 1(1);
    Codes(Flow2) = 0(0), 1(1);
    Codes(Flow3) = 0(0), 1(1);
    Codes(Flow4) = 0(0), 1(1);
    Codes(Flow5) = 0(0), 1(1);
    Model(Flow1) = 2PL;
    Model(Flow2) = 2PL;
    Model(Flow3) = 2PL;
    Model(Flow4) = 2PL;
    Model(Flow5) = 2PL;
    Mean = 0.0;
    Covariance = 1.0;

Constraints:

© 2022 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
