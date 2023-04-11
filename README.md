# routit-findings-april-11th-2023

## leesyprint 

flow

Route::get('getInboxMailsAndDetails', 'LeesyPrintMailController@getInboxMailsAndDetails')->name('getInboxMailsAndDetails');
Route::get('importJsonFile', 'LeesyPrintMailController@importJsonFile')->name('importJsonFile');
Route::get('submitLeesyPrintHostfactData', 'LeesyPrintHostfactController@submitLeesyPrintHostfactData')->name('submitLeesyPrintHostfactData');
