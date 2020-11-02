TO DO LIST APP (Jot-It)

User
   - has_many :lists
   - has_many :tasks, through: :lists
   

List
   - belongs_to :user
   - has_many :tasks
   - title/name(string)

Tasks
   - belongs_to :list
   - belongs_to :user
   - item(string)
   - description(string)
   - done/completed(boolean)
