# routit-findings-april-11th-2023

## leesyprint 

flow

Route::get('getInboxMailsAndDetails', 'LeesyPrintMailController@getInboxMailsAndDetails')->name('getInboxMailsAndDetails');
Route::get('importJsonFile', 'LeesyPrintMailController@importJsonFile')->name('importJsonFile');
Route::get('submitLeesyPrintHostfactData', 'LeesyPrintHostfactController@submitLeesyPrintHostfactData')->name('submitLeesyPrintHostfactData');

-before import // check current date or month and then check and match "period" => $data['period'],
-DONE

- AND ALSO DELETE THE FILE WHICH HAS BEEN FULLY IMPORTED
- DONE BUT COMMENTED

-also before submit to hostfact // check current date or month and then check and match "period" => $data['period'],
-DONE

- ** QUESTION - WE GET SO MANY FILES, WHICH ONE TO PICK? **
- ** QUESTION - MAIL WAS READ AND MOVED, NEED TO CHECK MAIL**
