<! DOCTYPE html > < html lang =" en" > < head > < meta charset =" utf-8" > < title > Task list </ title > < link rel =" stylesheet" type =" text/ css" href =" styles/ tasks.css" media =" screen" /> </ head > < body > < header > < span > Task list </ span > </ header > < main > < section > < form >
< div > < label > Task </ label > < input type =" text" required =" required" name =" task" class =" large" placeholder =" Breakfast at Tiffanys" /> </ div > < div > < label > Required by </ label > < input type =" date" required =" required" name =" requiredBy" /> </ div > < div > < label > Category </ label > < select name =" category" > < option value =" Personal" > Personal </ option > < option value =" Work" > Work </ option > </ select >
</ div > < nav > < a href ="#" > Save task </ a > < a href ="#" > Clear task </ a > </ nav > </ form > </ section > < section > < table id =" tblTasks" > < colgroup > < col width =" 50%" > < col width =" 25%" > < col width =" 25%" > </ colgroup > < thead > < tr > < th > Name </ th >


< th > Due </ th > < th > Category </ th > </ tr > </ thead > < tbody > < tr > < td > Return library books </ td > < td > < time datetime =" 2013-10-14" > 2013-10-14 </ time > </ td > < td > Personal </ td > </ tr > < tr class =" even" > < td > Perform project demo to stakeholders </ td > < td > < time datetime =" 2013-10-14" > 2013-10-14 </ time > </ td > < td > Work </ td > </ tr >

< tr > < td > Meet friends for dinner </ td > < td > < time datetime =" 2013-10-14" > 2013-10-14 </ time > </ td > < td > Personal </ td > </ tr > </ tbody > </ table > < nav > < a href ="#" > Add task </ a > </ nav > </ section > </ main > < footer > You have 3 tasks </ footer > </ body > </ html >

