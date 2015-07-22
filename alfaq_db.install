<?php
//смотри Schema API
//создали таблицу в БД
function alfaq_db_schema() {
    $schema ['alfaq_db'] = array();
    $schema ['alfaq_db'] = array(
        'description' => 'The my first table.',
        'fields' => array(
            'fe_id' => array(
                'description' => 'The primary identifier for a node.',
                'type' => 'serial',
                'unsigned' => TRUE,
                'not null' => TRUE,
            ),
            'mynumber' => array(
                'description' => 'field 1',
                'type' => 'int',
                'unsigned' => TRUE,
                'not null' => TRUE,
                'default' => 0,
            ),
            'mytextfield' => array(
                'description' => 'field 2',
                'type' => 'varchar',
                'length' => 255,
                'not null' => TRUE,
                'default' => '',
            ),
            'mytext' => array(
                'description' => 'field 3',
                'type' => 'text',
                'not null' => TRUE,
            ),
        ),
        'indexes' => array(
            'alfaq_db_mynumber' => array('mynumber'),
        ),
        'primary key' => array('fe_id'),
    );
    return $schema;
}

/*
function hook_install() {
    // Populate the default {node_access} record.
    db_insert('node_access')
        ->fields(array(
            'nid' => 0,
            'gid' => 0,
            'realm' => 'all',
            'grant_view' => 1,
            'grant_update' => 0,
            'grant_delete' => 0,
        ))
        ->execute();
}*/