public class LibraryApp {
    public static void main(String[] args) {
        // Создание объектов книг с помощью конструктора
        Book book1 = new Book("1984", "George Orwell", 1949);
        Book book2 = new Book("The Hobbit", "J.R.R. Tolkien", 1937);

        // Вывод информации о книгах
        book1.printBookDetails();
        book2.printBookDetails();

        // Предположим, что книгу "1984" взяли почитать
        book1.setAvailable(false);

        // Проверка, доступна ли книга "1984"
        if (!book1.isAvailable()) {
            System.out.println("The book " + book1.getTitle() + " is currently borrowed.");
        }

        // Добавление новой книги и изменение информации
        Book book3 = new Book("The Great Gatsby", "F. Scott Fitzgerald", 1925);
        book3.setYearPublished(1926); // предположим, что была ошибка в годе издания
        book3.printBookDetails();
    }
}
