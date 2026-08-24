# Solution Commands

#### Initialises directory with new Dataverse solution project
`pac solution init`

#### List all solutions from current Dataverse Organization
`pac solution list`

pac solution clone --name Solution1

#### Package solution components on local file system to solution.zip
`pac solution pack --zipfile c:\XX_1_0_0_1.zip --folder .\Sol_Unpack\ --packagetype Unmanaged`

#### Extract solution components from solution.zip into local file system
`pac solution unpack --zipfile c:\XX_1_0_0_1.zip --folder .\Sol_Unpack\ --packagetype Both`

#### Upload Dataverse solution project to run against Power Apps checker service
`pac solution check ?`

#### Export Solution
`pac solution export --path c:\YourSourceSolution.zip --name Solution-Name --managed false --include general`

#### Import Solution
`pac solution import --path c:\YourSourceSolution.zip -pc`

Push and publish active customizations in target environment
`pac solution publish`

`pac solution sync`




