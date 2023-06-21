# Урок 5. От простого к практике
* Сделать удаление из справочника пользователей
* Сделать сохранение в другом формате, например, не через запятую, а через точку с запятой, и разделителем - пустой строкой. 
* Предусмотреть сохранение в старом формате.

# Для уделения пользовтеля добавлены методы в классы:
* В класс ViewUser метод: private void delete()
* В класс UserController метод: public void deleteUser(String userId)
* В класс RepositoryFile метод: public void deleteUser(User user)

# Для работы с json добавлены класс:
* FileOperationJSON - унаследован от FileOperationImpl
* RepositoryFileJSON - унаследован от RepositoryFile
* UserMapperJSON - унаследование от UserMapper
 
