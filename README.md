# ETL for Sales Campaign

My client had several files recording email campaigns sent to their customer base. The client wants to use this data to see how sales people (Owners) are going with the campaigns. The hope is that account owners will be finding new opportunities and including them in the campaigns. Merely sending emails in successive campaigns to the same customers does not count as increasing the number of customers. The client wants to see that sales people are getting new customers and including them in campaigns, but this is not easily discovered when the campaign data is in several files and does not clearly differentiate between emails sent to the same customer vs. a new one.

To accommodate this need, I had to load all the data files into dataframes and concatenate them together. The file names contained important campaign information so this had to be extracted into columns. There was not a consistent way of representing campaign data in the file names, so this also had to be accommodated.

The client hoped to have a csv file returned that could be sorted and examined with normal Excel sort features. There was an additional file that associated each salerperson/owner with an account, and this was also to be included as an extra column in the final dataset. 

Through interviews with the client I discovered one of the purposes of this project, and included a separate csv file that answered the question: How many customers does each salesperson send campaigns to, for each campaign?

Specific details of file formats, both input and output, are described in the Jupyter Notebook for this project.