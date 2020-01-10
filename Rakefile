
namespace :db do
  
  task :migrate => :environment do
    Student.create_table
  end
  

  task :environment do
    require_relative './config/environment'
  end
  
  task :seed do
    require_relative './db/seeds.rb'
  end
  
  task :console => :environment do
    Pry.start
  end
  
end
