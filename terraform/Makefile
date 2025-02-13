ENV = ""
LOCK_ID = ""
RESOURCE_NAME = ""
RESOURCE_ID = ""
TARGET = "" 

reconfigure:
	bin/reconfigure ${ENV}

remote_plan:
	bin/remote_plan ${ENV}

local_plan:
	bin/local_plan ${ENV}

remote_target_plan:
	bin/remote_target_plan ${ENV} ${TARGET}

lock:
	bin/providers_lock

fmt:
	bin/fmt

force_unlock:
	bin/force_unlock ${LOCK_ID}

state_pull:
	bin/state_pull ${ENV}

state_push:
	bin/state_push ${ENV}

local_state_list:
	bin/local_state_list ${ENV}

local_state_rm:
	bin/local_state_rm ${ENV} ${RESOURCE_NAME}

local_state_import:
	bin/local_state_import ${ENV} ${RESOURCE_NAME} ${RESOURCE_ID}