# db.py
class Database:
    def __init__(self):
        self.users = {}    # user info
        self.files = {}    # uploaded files info

    def add_user(self, user_id, data):
        self.users[user_id] = data

    def get_user(self, user_id):
        return self.users.get(user_id)

    def add_file(self, file_id, data):
        self.files[file_id] = data

    def get_file(self, file_id):
        return self.files.get(file_id)

# single global instance
db = Database()
