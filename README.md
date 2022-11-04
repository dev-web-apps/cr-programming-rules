# cr-programming-rules

## Folder and File name Case (lowerCamelCase->PascalCase)

  example : 
  
    folderName -> FileName.tsx
    dashboard -> Dashboard.tsx
    
    
 ## Component (PascalCase)
 
    example :
      
      const Dashboard= () => {
        return (
          <h1> Welcome to dashboard !<h1/>
         )
      }
    
      export default Dashboard
      
      
  ## Function and Variable (lowerCamelCase)
      
      example :
      
        const userName=''
        const userEmail=''
        
        const handleChange= () => {
          // somthing
        }
        
   
   ## Constants / Enums (UPPERCASE)
   
      exapmle :
      
        const PI=3.142
        
        enum Direction {
          Up = "UP",
          Down = "DOWN",
          Left = "LEFT",
          Right = "RIGHT",
        }
        
   
   
   ## Folder Structure
    
      -assets
      -layouts
      -components
      -pages
      -routes
      -config
      -services
      -utils
 
   ## Folder Structure Nested
    
      -assets
          -images
          -icons
      -layouts
          -auth
          -main
      -components
          -card
              -Card.jsx
      -pages
           -home
              -Home.jsx
           -about
              -About.jsx
           -contact
              -Contact.jsx
      -routes
          -public
          -private
      -config
           -config.ts
      -services
            -dashboard
                dashboard.services.ts
      -utils
            -helpers
            -formatDate
            -formatNumber
 
      
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
  
    
