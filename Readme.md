# Nested column sorting
This Gem is used to sort nested columns in a table according to the attrribute provided by a user

**nested_column_sorting** can be used from the command line or as part of a Ruby web framework.

### Installation

To install the gem using terminal, run the following command:

    gem install nested_column_sorting

To use it in rails application add the gem to the Gemfile:

    gem "nested_column_sorting"    

### Basic Usage

nested_data = "*******" ( in json format )
column_name = "*******" ( string )

nested_column_sorting can sort nested column data in a table according to the parameter given by the user

    
    # The sort_nested_column_asc/sort_nested_column_dec methiod will sort the data according to the column name in ascending/descending order.

    Nested_Column::Sorting::Sort.new(nested_data, column_name).sort_nested_column_asc
    Nested_Column::Sorting::Sort.new(nested_data, column_name).sort_nested_column_dec
    



### To Do

specs
