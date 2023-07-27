class DigitalLibraryCLI:
    def __init__(self):
        self.books = {}

    def add_book(self, title, author, publication_year):
        book_id = len(self.books) + 1
        self.books[book_id] = {
            'title': title,
            'author': author,
            'publication_year': publication_year
        }
        print(f"Book with ID {book_id} added to the library.")

    def get_book(self, book_id):
        return self.books.get(book_id)

    def search_books_by_title(self, title):
        found_books = []
        for book_id, book_info in self.books.items():
            if title.lower() in book_info['title'].lower():
                found_books.append((book_id, book_info))
        return found_books

    def search_books_by_author(self, author):
        found_books = []
        for book_id, book_info in self.books.items():
            if author.lower() in book_info['author'].lower():
                found_books.append((book_id, book_info))
        return found_books

    def display_all_books(self):
        print("All books in the library:")
        for book_id, book_info in self.books.items():
            print(f"Book ID: {book_id}")
            print(f"Title: {book_info['title']}")
            print(f"Author: {book_info['author']}")
            print(f"Publication Year: {book_info['publication_year']}")
            print('-' * 30)

    def display_menu(self):
        print("\nDigital Library Menu:")
        print("1. Add a book")
        print("2. Search by title")
        print("3. Search by author")
        print("4. Display all books")
        print("0. Exit")

    def run(self):
        while True:
            self.display_menu()
            choice = input("Enter your choice: ")

            if choice == "1":
                title = input("Enter the title of the book: ")
                author = input("Enter the author of the book: ")
                publication_year = int(input("Enter the publication year: "))
                self.add_book(title, author, publication_year)
            elif choice == "2":
                search_title = input("Enter the title to search for: ")
                found_books = self.search_books_by_title(search_title)
                self.display_search_results(found_books, search_title)
            elif choice == "3":
                search_author = input("Enter the author to search for: ")
                found_books = self.search_books_by_author(search_author)
                self.display_search_results(found_books, search_author)
            elif choice == "4":
                self.display_all_books()
            elif choice == "0":
                print("Exiting the library. Goodbye!")
                break
            else:
                print("Invalid choice. Please try again.")

    def display_search_results(self, found_books, search_term):
        if found_books:
            print(f"Found books matching '{search_term}':")
            for book_id, book_info in found_books:
                print(f"Book ID: {book_id}")
                print(f"Title: {book_info['title']}")
                print(f"Author: {book_info['author']}")
                print(f"Publication Year: {book_info['publication_year']}")
                print('-' * 30)
        else:
            print(f"No books found matching '{search_term}'.")


if __name__ == "__main__":
    library = DigitalLibraryCLI()

    # Adding some books to the library
    library.add_book("Python Crash Course", "Eric Matthes", 2019)
    library.add_book("Automate the Boring Stuff with Python", "Al Sweigart", 2015)
    library.add_book("Fluent Python", "Luciano Ramalho", 2015)

    # Running the digital library
    library.run()
