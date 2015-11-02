# Import

Imprort is accessible only for admin users. Administration > Import. You are able to import only from CSV files.

## Step 1

Select what type of records you need to import (Entity Type field).
Select a CSV file. A file should be formated with UTF-8.
Select `What to do?`. Create Only, Create & Update, Update Only.

`Create Only` - select it if you want record be only created.
`Create & Update` - records will be created but if records with matching field values will be found it will be updated. You will be able to check what fields to match by on the Step 2.
`Update only` - only records with matching field values will be found it will be updated.

Once you select a csv file you will be able to see how it should be parsed in Preview panel. When you change properties the preview will be updated. 

## Step 2

Setup the field mapping: how fields correspond to columns of the csv file. You can skip not needed columns here.
In cases of 'Create & Update' and 'Update only' you need to check fields by which records that should be updated will be found.
Add default values you want new and updated records to set with. E.g. you can specify Assigned User or Teams fields.

After the import is done you will be able to revert created records, see duplicates and updated records. Duplicate means that there was the similar record in the system. You can remove all imported duplicates at once.

## How to import into Target List

When you import Contacts, Leads or Accounts you can add them to some target list. On the Step 2 you need to add Target List field on `Default Values` panel and select a needed target list record. You can also use `Update only` or `Create & Update` import to add existing targets to a target list.