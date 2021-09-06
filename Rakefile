namespace :greeting do

desc "outputs starter task"
  task :hello do
    puts "hello from Rake!"
  end

  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
  
  desc "outputs the newly created task return"
  task :making_my_own_task do
    puts "I have made my own task in rake!"
  end
  
  desc "require ./config/environment"
  task :environment do
    require_relative "./config/environment"
  end
  desc "migrate changes to your database"
  task migrate: :environment do
    Student.create_table
  end

end 

