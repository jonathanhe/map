class CreateLocations < ActiveRecord::Migration
  def change
    create_table :locations do |t|
      t.string :address
      t.float :latitude
      t.float :longitude

      t.timestamps
    end
    add_index :locations, :address
    add_index :locations, :latitude
    add_index :locations, :longitude
  end
end
