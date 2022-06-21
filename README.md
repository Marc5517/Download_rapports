# Download_rapports
# It first starts with preparations, where it changes the excel file into a Data Frame, deletes the NaN and replaces the empty spaces with values from the other column.
# Later it begins to download the PDF-files from it into a folder, and if the PDF-file doesn't meet the conditions, it looks through the second column, but still checks if those files meet the criteria.
# If it comes at an error, it will either skip it or go through the other column.
# While it downloads the files into the folder, it also checks which were downloaded and which were not, and writes it down into a Data Frame that later turns into an excel file.
