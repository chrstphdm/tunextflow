# NAME

tunextflow - standardise nextflow execution and log

# SYNOPSIS

tunextflow [OPTION]... [ACTION]

# DESCRIPTION

tunextflow can generate, run and list runs history of nextflow projects. 

# ACTION

The following actions are available :

## generate

Generate execution files without running.

    tunextflow -p <my_nextflow_project_folder> generate

## run

Generate and run a nextflow project.

    tunextflow -p <my_nextflow_project_folder> run

## config

Print params/configs/libs files that would be used to generate execution files and run a nextflow project.

    tunextflow -p <my_nextflow_project_folder> config

## log

Print informations matching with criterias for runs.

    tunextflow -p <my_nextflow_project_folder> log
    tunextflow -p <my_nextflow_project_folder> --status running log
    tunextflow -s error log

## check

    TODO

## env

    TODO

## update

    TODO

# OPTION

The following options are available :

## -c|--config_dir

    Folder for config files. 

## -l|--lib_dir
    
    Folder for library files

## -m|--param_dir
    
    Folder for param files

## -p|--project_dir

    Folder for project files

## -r|--run_dir

    Folder used to launch project pipeline

## -s|--status

    Execution status filter [NEW,SUBMITTED,RUNNING,COMPLETED,FAILED,ABORTED]

## -b|--before

    Before timestamp filter

## -a|--after

    After timestamp filter

## -f|--fields



## -u|--uuid


