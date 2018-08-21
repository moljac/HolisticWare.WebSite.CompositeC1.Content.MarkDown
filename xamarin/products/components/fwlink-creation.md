# `fwlink` Creation

fwlink-creation.md

## Steps
*   goto 

    https://sftools.trafficmanager.net/redirection/home?options=host:go.microsoft.com

*   Data:

    *   Target Link

        link the `fwlink` is created for

    *   Product: 
    
        `Visual Studio (12514)`

    *   SBP (Sub Prod): 
    
        `Xamarin Components`

    *   AR (Area): 
    
        `XamarinComponents`

    *   SBA (Sub Area): 
    
        `ProjectUrl` || `LicenseUrl`

    *   Security Group Alias (as a Link Owner) 

        `xamarin-components`


just have a look at an old link


## Example

*   Data:

    *   Target Link

        https://github.com/grpc/grpc/blob/master/LICENSE

*   Security Group (SG)

    xamarin-components 
    
    security group for any newly created

*   NOTES

    link is just a number so it should be safe to just create a new one

Sample 2:

*   Data

    *   Target URL* 

        https://github.com/xamarin/XamarinComponents/tree/master/XPlat/OpenId

    *   Mobile URL 
        
    *   Description 

        Xamarin.OpenId.AppAuth.Android NuGet Project Url

    *   PRD (Product)*

        Visual Studio (12514)

    *   SBP (Sub Product) 

        Xamarin Components

    *   AR (Area)* 

        XamarinComponents

    *   SBA (Sub Area)* 

        ProjectUrl

        LicenseUrl

    *   Security Group Alias (as a Link Owner) 

        xamarin-components


Sample 3

*   Data for GRPC

    *   TargetURL
    
        *   https://github.com/xamarin/XamarinComponents/tree/master/XPlat/Google.Grpc

        *   ProjectUrl

    *   fwlink
    
        *   https://go.microsoft.com/fwlink/?linkid=2009337&clcid=0x409

        *   LicenseUrl

        *   https://github.com/xamarin/XamarinComponents/blob/master/XPlat/Google.Grpc/LICENSE.md

        *   https://go.microsoft.com/fwlink/?linkid=2009338&clcid=0x409