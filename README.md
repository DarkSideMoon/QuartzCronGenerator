# QuartzCronGenerator ⚙️

## Bootstrap-5 Cron expressions generator

**quartzCron** is a Jquery plug-in which helps you to build cron expressions. 
**quartzCron** generated expressions are based on `Quartz` cron format. 

## Sample 
Sample of project you can find by the [link](https://darksidemoon.github.io/QuartzCronGenerator/) on github pages

## Dependencies

 * [jQuery](https://jquery.com/)
 * [bootstrap](https://getbootstrap.com/)

## Usage

  Intialization:
  
      $(element).quartzCron();
      
  Getting Cron Expression:
  
    var cron = $("element").quartzCron();
    alert(cron.getCron)
    
  Setting CRON Expression:
  
    $("element").quartzCron({
        setCron: '0 0 12 1/1 * ? *'
        activeTab: “DAILY”
    });