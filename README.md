# QuartzCronGenerator 

## Bootstrap-5 Cron Expressions generator ⚙️

**msCron** is a Jquery plug-in which helps you to build cron expressions. 
**msCron** generated expressions are based on `Quartz` cron format. 

## Dependencies

 * [jQuery](https://jquery.com/)
 * [bootstrap](https://getbootstrap.com/)

## Usage

  Intialization:
  
      $(element).msCron();
      
  Getting Cron Expression:
  
     var cron = $("element").msCron();
     
    alert(cron.getCron )  //you can get the required CRON expression
    
  Setting CRON Expression:
  
    $("element").msCron({
        setCron: “0 0 12 1/1 * ? *”
        activeTab: “DAILY”
    });